### IKO

**Context and definitions**

| **Definition** | **Explanation** |
| --- | --- |
| Backend service | A Service exposing data. A service can be based on the HaalCentraal principle, standardized Common Ground API’s, or municipality-speficis legacy services. |
| Profile | Configuration of a data view. A profile can include data from multiple backend services. A profile refers to data from a backend service on attribute level. Profiles are used to combine data from multiple sources, and to restrict access to data. Profiles are configured in JSON. |
| Widget | Configuration of the visual representation of data in GZAC. A widget configuration includes a widget type (fields, list), layout settings (size, color), which properties are shown (paths), the type of data (text, date) and optional format details (date format). One widget can only contain paths from one profile. Multiple widgets can be configured on a widget tab. |
| Access control | Access control is implemented by first defining profiles, and granting access to those profiles to user roles. |
