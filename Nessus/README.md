# Nessus - Vulnerability Scanner

- Nessus is a popular network host scanner used by cybersecurity personnel to detect, analyze and mitigate various vulnerabilities in the network architecture of the target host.
- Nessus Essentials is the free version of Nessus that can be used to scan 16 hosts. If you want more access to advanced features and more hosts, you can buy the paid `Expert` and `Professional` version.

![nessus](https://user-images.githubusercontent.com/70995581/230767302-49d2c28c-ad09-4894-a918-1cc136828129.png)

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
>**Note**: Make sure you have a active internet connection to download plugins, do not select `Register Offline`. Select `Continue`.
- Select `Register for Nessus Essentials > Continue`.

![Screenshot from 2023-04-09 10-07-07](https://user-images.githubusercontent.com/70995581/230768011-eeeb2f67-2b29-4ffe-9ac7-84113887c023.png)

- Enter your Activation Code from earlier.

![Screenshot from 2023-04-09 16-08-41](https://user-images.githubusercontent.com/70995581/230767937-c436baad-45ae-4c75-8f2d-b102633f41fd.png)
- Create new Nessus `username` and `password`

![Screenshot from 2023-04-09 10-15-51](https://user-images.githubusercontent.com/70995581/230768087-e3d61f3a-00d2-4e95-b170-018a66577646.png)
- Wait few moments for the necessary plugins to be downloaded.
 
 ![Screenshot from 2023-04-09 10-16-13](https://user-images.githubusercontent.com/70995581/230768165-25b2255e-a451-4efd-9a6c-79c78f55c970.png)
- Nessus:

![Screenshot from 2023-04-09 11-25-32](https://user-images.githubusercontent.com/70995581/230768279-a56ca701-a35f-4281-bf6b-27e1c4f24feb.png)

- Create a new scan:

![Screenshot from 2023-04-09 11-25-45](https://user-images.githubusercontent.com/70995581/230768240-b751967f-a38e-42bb-8ec7-db6c191125b8.png)

