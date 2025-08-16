# YouCook2-JP

©2025, The University of Tokyo

Japanese translation of the [YouCook2](http://youcook2.eecs.umich.edu/) dataset. 

Our dataset is an extention of the original [YouCook2](http://youcook2.eecs.umich.edu/) dataset. We do not own the copyrights of raw videos, English captions, and annotations in YouCook2. For the use of data in YouCook2, please refer to their website for details on the contents of the dataset, how to use it, and copyright information.

**(2025 August) We are going to organize [English-Japanese Video Translation Task](https://nlab-mpg.github.io/wat2025-vct-jp/) at [WAT2025](https://lotus.kuee.kyoto-u.ac.jp/WAT/WAT2025/index.html)!**


## License
Our dataset is released under the [MIT license](LICENSE.txt).

## Dataset Description
We provide Japanese translations for all English captions in the training and validation splits in YouCook2. (Note that captions of testing data are not made public in YouCook2.)
Translation is manually carried out by a professional team in a Japanese translation company, who carefully translate the English captions while referring to the corresponding video to produce high-quality (less ambiguous) and visually-grounded translations.

Japanese captions corresponding to English captions for each segment of each video are stored in a json file encoded in UTF-8 format. It follows the same structure and tags as the annotation file provided in YouCook2 ([youcookii_annotations_trainval.json](http://youcook2.eecs.umich.edu/download)).

- [youcookii_translations_ja_train.json](youcookii_translations_ja_train.json) (training)
  
Currently, only the training set has been released since we are using the validation set as the testing dataset for the ongoing [WAT2025 competition](https://nlab-mpg.github.io/wat2025-vct-jp/). We are planning to release the validation set after the competition is finished. 

## Reference
If you use this dataset, please cite this web page.

```
@misc{example,
  title = {YouCook2-JP dataset},
  author = {Hideki Nakayama},
  institution={The University of Tokyo},
  howpublished = {\url{https://github.com/nlab-mpg/YouCook2-JP/}},
  year = {2025}
}
```
## Acknowledgment
This project is supported by the Commissioned Research (No.225) by the National Institute of Information and Communications Technology (NICT), JAPAN.  
