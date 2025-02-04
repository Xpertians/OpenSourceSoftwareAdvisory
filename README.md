# Open Source Software Advisory (OSSA) - Database

## Overview
The **Open Source Software Advisory (OSSA) Database** is a community-driven repository that collects and maintains structured advisories for open-source packages. These advisories highlight issues such as package deprecations, license concerns, security risks, and other factors affecting software sustainability.

This repository is designed to be **neutral and independent**, providing information that is **generic and not tied to any specific organization, use case, or company**. It serves as a **reference database** for Open Source ecosystems and does **not constitute legal advice**.

## Repository Contents
- **`advisories/`** – The directory containing JSON advisory files following the OSSA schema.
- **`docs/`** – Documentation related to the schema and advisory guidelines.

## Advisory Structure
Each advisory is formatted according to the **OSSA Schema** and contains:
- **Unique Identifier** (`id`)
- **Package Details** (`package_name`, `purls`)
- **Severity Assessment** (`severity`, `affected_versions`)
- **Approvals & Metadata** (`approvals`, `last_updated`)
- **External References** (`references`, `licenses`)

For full details, refer to the [`OSSA Advisory Schema`](https://github.com/Xpertians/OpenSourceSoftwareAdvisory-spec).

## License
All content in this repository is licensed under the **MIT License**. See the [`LICENSE`](LICENSE) file for details.

## Disclaimer
- This repository provides **general information** about Open Source Software Advisories.
- It is **not specific to any company, project, or use case**.
- It **does not constitute legal or compliance advice**.

## Contributing
Contributions are welcome! To contribute:
1. Fork the repository.
2. Add or update an advisory in the `advisories/` directory.
3. Validate your changes using the OSSA validator.
4. Submit a pull request.

For discussions and improvements, please open an issue.

