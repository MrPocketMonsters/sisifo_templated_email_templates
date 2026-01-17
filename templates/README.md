# Templates Folder

This folder contains HTML templates used for generating email notifications in the SÍSIFO system. Each template is designed to format specific types of emails, such as requests for document reviews or approvals.

## Available Templates

- `SISIFO_PLANTILLA_SOLICITUD.html`: This template is used for sending notifications about new requests related to audit documents. It includes placeholders for dynamic content such as the audit name, document name, request type, and validity period.

  **Placeholders:**

  - `{{titulo_solicitud}}`: The title of the request. Usually indicates the type of request (e.g., review, approval) and the name of the audit project.
  - `{{tipo_solicitud}}`: The type of request being made (e.g., review, approval).
  - `{{nombre_documento}}`: The name of the document associated with the request.
  - `{{vigencia}}`: The validity year for the document.
  - `{{rol_remitente}}`: The role of the sender in the SÍSIFO system.
  - `{{nombre_remitente}}`: The name of the sender.
  - `{{fecha_envio}}`: The date the request was sent.

- `SISIFO_PLANTILLA_RECHAZO.html`: This template is used for sending notifications about document rejections in the SÍSIFO system. It includes placeholders for dynamic content such as the rejection title, document name, validity period, and reason for rejection.
  **Placeholders:**
  
  - `{{titulo_rechazo}}`: The title of the rejection. Usually indicates the rejected document and the name of the audit project.
  - `{{nombre_documento}}`: The name of the document that has been rejected.
  - `{{vigencia}}`: The validity year for the document.
  - `{{motivo_rechazo}}`: The reason for the document's rejection.
  - `{{rol_remitente}}`: The role of the sender in the SÍSIFO system.
  - `{{nombre_remitente}}`: The name of the sender.
  - `{{fecha_envio}}`: The date the rejection notification was sent.
