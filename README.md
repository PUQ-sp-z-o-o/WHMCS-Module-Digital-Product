# WHMCS-Module-Digital-Product
Provides the opportunity to sell digital products in WHMCS by sharing Nextcloud resources.

- - - - - -

# Description

### Digital Product module **[WHMCS](https://puqcloud.com/link.php?id=77)** 

#####  [Order now](https://puqcloud.com/index.php?rp=/store/whmcs-module-digital-product) | [Download](https://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-Digital-Product/) | [FAQ](https://faq.puqcloud.com/)

### Preface

With this module, your company can offer customers the ability to purchase DIGITAL PRODUCTS, which they can then download from a Nextcloud cloud server.

The module is designed to create a personalized link for downloading a resource (folder) from a pre-configured Nextcloud server. It allows for the creation, blocking, and unblocking of access to digital products, and disables access in case of non-payment.

#### How It Works:

1. **Nextcloud Server Setup**: 
    - Set up your Nextcloud server and create directories in the root directory for the digital products you want to sell to customers.
2. **Product Creation in WHMCS**:
    - Use the module to create products in WHMCS and specify the folder on the Nextcloud server that should be available for download to the customer after payment.
3. **Customer Purchase and Access**:
    - After a customer purchases and pays for a product, the module will create a personalized shared link to the purchased resource, allowing the customer to view and download the acquired digital product.
4. **Access Management**:
    - If the customer cancels the subscription or fails to make a payment, the module will automatically block the access link during the non-payment period. Once the payment is completed, the link to the resource will be unblocked.
    - In the event of service termination, the personalized shared link to the resource will be deleted.
5. **Security Options**:
    - The link can be configured to require a password or to be accessible without a password, providing flexibility in securing the shared resources.

This module integrates seamlessly with WHMCS, enabling efficient management and delivery of digital products through Nextcloud, ensuring your customers have a smooth and secure download experience.

>For the correct operation of the module, a pre-prepared Nextcloud installation is required (the module does not assist in the installation of the Nextcloud server and assumes that such installation is ready for operation through API.) Module use Nextcloud API to manage share.

>We have prepared a detailed installation manual for the module, including all the steps needed to implement the module, including the preparation of the Nextcloud server, including all installation steps such as NGNIX, PHP, Nextcloud, SSL certificates etc.

### Functions:

- Auto Create/Suspend/Unsuspend/Terminate share url to download digital product
- The module uses only the API to manage Nextcloud share
- Module supports multilingualism **(Arabic, Azerbaijani, Catalan, Chinese, Croatian, Czech, Danish, Dutch, English, Estonian, Farsi, French, German, Hebrew, Hungarian, Italian, Macedonian, Norwegian, Polish, Romanian, Russian, Spanish, Swedish, Turkish, Ukrainian)**

### Available options in the admin panel:

- Create
- Suspend
- Unsuspend
- Terminate
- API connection status

### Available options in the client panel:

- URL to download
- URL to user manual

- - - - - -

>WHMCS minimal version: 8 +

>Nextcloud minimal version: 20+

[![image-1717984839294.png](https://doc.puq.info/uploads/images/gallery/2024-06/scaled-1680-/image-1717984839294.png)](https://doc.puq.info/uploads/images/gallery/2024-06/image-1717984839294.png)

[![image-1717984907008.png](https://doc.puq.info/uploads/images/gallery/2024-06/scaled-1680-/image-1717984907008.png)](https://doc.puq.info/uploads/images/gallery/2024-06/image-1717984907008.png)
