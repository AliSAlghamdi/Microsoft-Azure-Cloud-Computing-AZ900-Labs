## **Lab 2 - Configure a Web Server on Azure Virtual Machine**

### 🎯 **Objective**
Learn how to configure a web server (NGINX) on an existing Azure Virtual Machine and host a simple web page.

---

### ⚙️ **Steps**

**1.** Open **Azure Cloud Shell** and list the virtual machines using the command:
```bash
az vm list -d -o table
2. Connect to the running VM using SSH.

3. Install NGINX web server:

bash
نسخ الكود
sudo apt update
sudo apt install nginx -y
4. Navigate to the NGINX web directory:

bash
نسخ الكود
cd /var/www/html
5. Edit the default webpage:

bash
نسخ الكود
sudo nano index.html
6. Modify the page content to display:

html
نسخ الكود
<h1>Welcome to Azure! I am Ali Alghamdi</h1>
7. Adjusted the design to center the text and increase the font size using simple CSS styling.

8. Open the public IP of the VM in a browser to verify the result.

📸 Screenshots
ex22.png – Shows the VM details in Azure Cloud Shell.

ex23.png – Shows the hosted web page displaying the message “Welcome to Azure! I am Ali Alghamdi”.

✅ Result
The NGINX web server was successfully configured on the Azure VM, and the custom webpage loaded correctly in the browser.

yaml
نسخ الكود
