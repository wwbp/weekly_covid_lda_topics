# Understanding Weekly COVID-19 Concerns through Dynamic Content-Specific LDA Topic Modeling.

A set of 40 covid-related topics (per week) derived from Twitter starting on March 12, 2020. 

Read the full publication [here](https://www.aclweb.org/anthology/2020.nlpcss-1.21/). 

## Topics

Each week's topics are available in csv format.

### week_*_cp

* `id`: auto-incremented numeric row id
* `term`: unigram in topic
* `category`: Numeric topic id (from 0 to 39)
* `weight`: Conditional probability of the topic given the unigram, as derived through the LDA process. 

### week_*_loglik

* `id`: auto-incremented numeric row id 
* `term`: unigram in topic
* `category`: Numeric topic id (from 0 to 39)
* `weight`: Posterior likelihood

## Dates

* Week 1: begins March 12, 2020
* Week 2: begins March 19, 2020
* Week 3: begins March 26, 2020
* Week 4: begins April 02, 2020
* Week 5: begins April 09, 2020

## Citation

Please cite the following paper if you use this data. 

```
@inproceedings{zamani2020understanding,
    title = "Understanding Weekly COVID-19 Concerns through Dynamic Content-Specific LDA Topic Modeling",
    author = "Zamani, Mohammadzaman  and
      Schwartz, H. Andrew  and
      Eichstaedt, Johannes  and
      Guntuku, Sharath Chandra  and
      Ganesan, Adithya Virinchipuram  and
      Clouston, Sean  and
      Giorgi, Salvatore",
    booktitle = "Proceedings of the Fourth Workshop on Natural Language Processing and Computational Social Science",
    year = "2020",
    publisher = "Association for Computational Linguistics",
}
```

## Contact

Please contact mzamani [at] cs [dot] stonybrook [dot] edu with any questions.

## License

Licensed under a GNU General Public License v3 (GPLv3).

