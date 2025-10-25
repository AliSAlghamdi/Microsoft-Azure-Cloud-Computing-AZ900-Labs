# Lab 4 - Azure Blob Storage

In this lab, I created and configured an Azure Storage Account, then uploaded a blob (image) and made it publicly accessible.

## Steps

1. **Create a Storage Account**
   - Resource Group: `IntroAzureRG`
   - Storage Account Name: `alistoragelab01`
   - Region: `UAE North`
   - Performance: `Standard`
   - Redundancy: `LRS (Locally Redundant Storage)`

   ![Create Storage Account](../Lab4-BlobStorage/ex41.png)

2. **Configure Advanced Settings**
   - Enabled secure transfer
   - Allowed anonymous access on containers

   ![Advanced Settings](../Lab4-BlobStorage/ex42.png)

3. **Review and Create**
   ![Review](../Lab4-BlobStorage/ex43.png)

4. **Deployment Completed**
   ![Deployment Complete](../Lab4-BlobStorage/ex44.png)

5. **Create Container**
   - Name: `images`
   - Access level: Private (initially)

   ![Create Container](../Lab4-BlobStorage/ex45.png)

6. **Upload Blob**
   - File: `ksa.png`

   ![Upload Blob](../Lab4-BlobStorage/ex46.png)

7. **Change Access Level**
   - To: `Blob (anonymous read access for blobs only)`

   ![Access Level](../Lab4-BlobStorage/ex47.png)

8. **Test Public Access**
   - URL: [ksa.png](https://alistoragelab01.blob.core.windows.net/images/ksa.png)

   ![KSA Flag](../Lab4-BlobStorage/ex48.png)

---

✅ **Result:**  
The image is publicly accessible through Azure Blob Storage.

🌍 **Public link:**  
[https://alistoragelab01.blob.core.windows.net/images/ksa.png](https://alistoragelab01.blob.core.windows.net/images/ksa.png)
