### Integraal Klant- en Objectbeeld (IKO)

**Context and definitions**

| **Definition** | **Explanation** |
| ----- | --- |
| Backend service | A service exposing data. A service can be based on the centralized HaalCentraal principle, standardized local Common Ground API’s, or municipality-specific legacy services. |
| Primary source | A backend service that can be used as a primary entry point for customers. Primary sources can be used to search. Example: BRP (personen), KVK (bedrijven) or BAG (panden) |
| Secondary source |  A backend service that can be used for retrieving additional data. End users can not search directly in secundairy sources, but they are available to retrieve data based on a customer/object identifier |
| Profile | Configuration of a data view. A profile can include data from multiple backend services. A profile refers to data from a backend service on attribute level. Profiles are used to combine data from multiple sources, and to restrict access to data. Profiles are configured in JSON. |
| Widget | Configuration of the visual representation of data in GZAC. A widget configuration includes a widget type (fields, list), layout settings (size, color), which properties are shown (paths), the type of data (text, date) and optional format details (date format). One widget can only contain paths from one profile. Multiple widgets can be configured on a widget tab. |
| Access control | Access control is implemented by first defining profiles, and granting access to those profiles to user roles. |
