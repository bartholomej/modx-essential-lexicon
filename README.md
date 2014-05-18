# MODx Essential Custom Lexicon
Tiny custom lexicon for MODx Revolution includes essential words and phrases .) (alpha)

Lexicon includes:
* Essential phrases (eg. More Info, View more, Hot news, ...)
* Days of the week
* Months
* ...

## Installation
Just download the source code from GitHub and copy to your MODx folder.

	path-to-your-modx-installation/core/lexicon/*

## Documentation
### Using example
	[[%learn_more? &language=`[[++cultureKey]]` &namespace=`core` &topic=`app`]]

#### Language variable examples
* **Placeholder:** ```[[++cultureKey]]``` (easy to use with Babel addon)
* **Snippet:** ```$modx->getOption('cultureKey');``` or ```return $modx->context->key;```  

### Editing phrases in manager
**Step 1:** Login to your MODx Manager

**Step 2:** Go to System -> Lexicon

**Step 3:** Switch topic to **app**

## License
I welcome you to customize this according to your needs or add other language. 
Pull requests for any improvements would be great!

## Developed by
* BART! - http://google.com/+LukasBartak, https://github.com/bartholomej