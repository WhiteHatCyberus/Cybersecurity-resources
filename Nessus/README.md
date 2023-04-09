# Nessus - Vulnerability Scanner

- Nessus is a popular network host scanner used by cybersecurity personnel to detect, analyse and mitigate various vulnerabilities in the network architecture of the target host.
- Nessus Essentials is the free version of Nessus that can be used to scan 16 hosts. If you want more access to advanced features and more hosts, you can buy the paid `Expert` and `Professional` version.

# Installation

- Firstly, if you're installing Nessus for the first time, register for an Nessus Essentials Activation Code [here](https://www.tenable.com/products/nessus/nessus-essentials).

![Screenshot from 2023-04-09 10-09-09](https://user-images.githubusercontent.com/70995581/230766364-62d92d80-cf63-4aa0-9ea2-0337f8f6452e.png)

- Copy the activation code sent to your given email.

![Screenshot from 2023-04-09 10-12-57](https://user-images.githubusercontent.com/70995581/230766424-32697b80-d002-47a0-935d-4a2ef0252587.png)

- `Download Nessus`. Select the Nessus Release `Version` and the `Platform`.

![Screenshot from 2023-04-09 10-03-43](https://user-images.githubusercontent.com/70995581/230766537-50a5fae8-9bcd-4bc3-8576-f6c9bb4f8979.png)

- Open the terminal in the directory where the `.deb` file is downloaded. Run the command:

```bash
sudo dpkg -i <Nessus_package.deb>
```
![Screenshot from 2023-04-09 10-04-52](https://user-images.githubusercontent.com/70995581/230766734-c63f8dbb-ce55-4029-b992-048a4a7ea118.png)

![Screenshot from 2023-04-09 10-05-08](https://user-images.githubusercontent.com/70995581/230766753-e0600b10-df6c-45e4-bdb2-03d17c5aa3cf.png)
- After Installation. Start the Nessus service:

```bash
sudo systemctl start nessusd.service
```
![Screenshot from 2023-04-09 10-05-39](https://user-images.githubusercontent.com/70995581/230766847-fc7e3a7f-51a0-4eab-9ea4-bbe9ac4f3289.png)

- Go to `https://localhost:8834` in your browser.

![Screenshot from 2023-04-09 10-06-13](https://user-images.githubusercontent.com/70995581/230767053-99039c20-f2d2-4407-a696-bb42fe619595.png)

- Configure Nessus.

![Screenshot from 2023-04-09 10-06-54](https://user-images.githubusercontent.com/70995581/230767100-26e448f7-a614-4690-bce8-3146127aa8b6.png)
>**Note** Make sure you have a active internet connection to download plugins, do not select `Register Offline`.
