# LexiconX for MODX
Tiny custom lexicon for MODX Revolution includes essential words and phrases .)

**Lexicon includes:**
* Essential phrases (eg. More Info, View more, Hot news, ...)
* Days of the week
* Months
* Registration form
* ...

## Installation
Just install latest package located here in `_packages` directory

## Documentation
### Usage example
	[[%learn_more? &language=`[[++cultureKey]]` &namespace=`lexiconx` &topic=`default`]]

#### Language variable examples
* **Placeholder:** ```[[++cultureKey]]``` (easy to use with Babel addon)
* **Snippet:** ```$modx->getOption('cultureKey');``` or ```return $modx->context->key;```  

### Customizing strings in manager
* **Step 1:** Login to your MODx Manager
* **Step 2:** Go to **Settings** -> **Lexicons**
* **Step 3:** Switch namespace to **lexiconx**

_Notice: In MODX Revolution, however, the strings are still in the files, but if you change the strings properly, the new version is stored in the MODX database, where it will survive any upgrades. [Bobs's Guide](http://bobsguides.com/blog.html/2013/05/22/customizing-lexicon-strings-in-modx-revolution/)_


## License
I welcome you to customize this according to your needs or add other language. 
Pull requests for any improvements would be great!

## Created by
* BART! - http://google.com/+LukasBartak, https://github.com/bartholomej