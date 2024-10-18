# DEQ File Synchronization Process API (deq-filesync-papi)

**deq-filesync-papi** is a MuleSoft-based Process API that facilitates the bidirectional synchronization of documents between **Salesforce** and **Laserfiche** for the **Department of Environmental Quality (DEQ)**. This integration aims to streamline the document management process, ensuring that files are consistently and securely transferred between the two systems based on business needs.

## Key Features

- **Event-Driven Synchronization**: The API subscribes to **Salesforce Platform Events** to handle document transfers, enabling a responsive synchronization process.
- **Bidirectional Document Flow**: Allows documents to be uploaded to Laserfiche from Salesforce and retrieved back into Salesforce, ensuring data consistency across both platforms.
- **Metadata Management**: Ensures consistent handling of document metadata such as **Application ID**, **Document ID**, and **Laserfiche ID** to maintain document integrity throughout the synchronization process.
- **Scalable and Reliable**: Built on **MuleSoft's CloudHub 2** platform, providing high availability and scalability to meet current and future business requirements.

## Overview

The **deq-filesync-papi** is a core component of the Salesforce-Laserfiche integration for DEQ. It provides a robust solution for managing document uploads, synchronization, and retrieval while ensuring control remains with the **back-office staff**. By leveraging the event-driven capabilities of Salesforce and the powerful integration capabilities of MuleSoft, this API plays a key role in enhancing document handling efficiency while minimizing manual efforts and reducing the risk of human error.

## Deployment

The **deq-filesync-papi** is deployed on **MuleSoft's CloudHub 2**, which provides seamless integration and scalability for the Department of Environmental Quality's needs. The API is part of an API-led connectivity approach, ensuring modularity and ease of integration with other systems if needed in the future.

## Future Enhancements

Planned improvements for the **deq-filesync-papi** include:

- **Queue Management**: Implementing queue management to improve message reliability and guarantee successful delivery, even in case of transient errors.
- **Enhanced Automation**: Improving Salesforce workflows to automatically detect conditions for synchronization, further reducing manual intervention.

## Getting Started

To start using **deq-filesync-papi**:

1. Clone the repository.
2. Follow the setup instructions to deploy the API to your MuleSoft environment.
3. Configure Salesforce Platform Events to initiate document synchronization actions.

For more detailed setup instructions, please refer to the [Documentation](docs/setup.md).

---

**License**: MIT License. See the [LICENSE](LICENSE) file for more details.
