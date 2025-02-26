# protocols

Inventory of protocols used by the GCL

---

## Organization

* The readme will provide an organized set of links and instructions for maintaining this repo.
* Each protocol will be detailed in a markdown document in the [protocols](protcols) dir
* Files associated with each protocol will be stored in the [accessory_files](accessory_files) dir and must be linked in the protocol that uses them
* Scripts associated with the protocols will be stored in the [scripts](scripts) dir
* Each new protocol should be created from the [protocol template](protocols/protocol_template.md) markdown doc 
* If this organization scheme doesn't work for a particular protocol, bring this to the attention of @cbird808 to solve

---

## Protocol Naming

`reaction-category_protocol-name_rxn-format`

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
 
