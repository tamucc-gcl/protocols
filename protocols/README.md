# Protocols

This directory contains all of the GCL protocols

---

## Create a New Protocol

Use the [protocol template](protocol_template.md) to create a new protocol.  Be sure not to overwrite it.

---

<details>
<summary><strong>Protocol File Naming</strong></summary>

`reaction-category_protocol-name_rxn-format.md`

* `reaction-category` is the category of the reaction. Do not make up a new category name if an appropriate one already exists. The list of categories follows here.  If you create a new category, add it to this list in alphabetical order
	* cleanup
	* extraction
	* pcr 
	
* `protocol-name` is the unique name of the protocol, without considering the reaction format (see below). Add protocol names below in alphabetical order
	* replace this text with the name of the first protocol

* `num-rxn-format` is the format of the reaction
	* 1-tube
	* 8-tube-strip
	* 96-well-plate
	* 384-well-plate

</details>

---

<details>
<summary><strong>Version Control Guidelines</strong></summary>

These guidelines describe best practices for managing protocol versions using Git and ensure clarity, traceability, and reproducibility in your projects.

---

## 1. Embed Version Metadata

Include the following metadata in each protocol file:
- **Author**: The person who created or last updated the protocol.
- **Date Created**: The date the protocol was initially created.
- **Last Updated**: The date of the most recent update.
- **Version**: Use semantic versioning (e.g., `1.0.0`, `1.1.0`, etc.).
- **Tags**: Keywords for categorization (e.g., extraction, cleanup, PCR).

---

## 2. Use Commit History Effectively

- **Commit Often**: Make frequent, incremental commits to capture small changes.
- **Descriptive Commit Messages**: Write clear, concise messages that explain *what* changed and *why*.
- **Atomic Commits**: Each commit should address a single, logical change for easier review and reversion if needed.

---

## 3. Branching and Pull Requests

- **Feature Branches**: Develop new features or updates on separate branches.
- **Pull Requests for Merging**: Use pull requests to review and merge changes into the main branch.
- **Maintain a Stable Main Branch**: Only merge changes that have been thoroughly tested to ensure stability.

---

## 4. Tagging and Releases

- **Tag Releases**: Use Git tags (e.g., `v1.0.0`, `v1.1.0`) to mark significant protocol versions.
- **Release Notes**: Document major changes, bug fixes, or enhancements in release notes or a changelog.

---

## 5. Maintain a Changelog

- **CHANGELOG.md**: Keep a separate file or include a section in your protocols that logs:
  - Date of change
  - Version number
  - Author of the change
  - Brief description of the change
- **Regular Updates**: Update the changelog with every significant change to track the evolution of your protocols.

---

## 6. Continuous Integration and Testing

- **Automated Builds**: Use CI tools to automatically build and test changes before merging.
- **Pre-Merge Testing**: Ensure that all changes pass tests on their respective branches to minimize conflicts and maintain code integrity.

---

## 7. Access Control and Collaboration

- **Limit Access**: Grant repository access only to necessary team members.
- **Peer Reviews**: Encourage code reviews and discussions via pull requests to improve quality and share knowledge.

---

## Conclusion

By following these version control guidelines, your team will maintain a clear, organized, and reliable history of protocol changes. This fosters collaboration, simplifies troubleshooting, and ensures that protocols are reproducible and easy to manage over time.

---

Protocol Inventory


</details>
