# Tang History Database - Name Syllable Challenge
**Jeff Heller, Data and Project Coordinator - East Asian Studies, Princeton University**

*April 26, 2019*

A biography in the Old and New Tang History will typically begin with a figure's full name (both family and given name) mentioned in the introductory paragraph. From that point, however, the figure is mentioned only by their given name. Chinese names do not use spaces as delimiters like with English names (e.g. Wenren Suian, 聞人遂安), therefore it is difficult to determine when the given name appears after its initial mention in the text. However, each syllable in a Chinese name is its own character. Therefore, this process counts the number of syllables in the English family and given name and then uses that result to determine the Chinese given name of the person.

Please be aware that the structure of this notebook is untraditional in that it details the process of its creation in reverse order.

## The Completed Function and Results
The success of the project is based heavily on the romanization of Chinese names. Romanization does not employ "ye olde European" spelling trickery with multiple silent letters (e.g. "esque" pronounced as *esk* instead of *esk-uh*, "Champagne" pronounced as *sham-payn* instead of *sham-pog-nuh*). Therefore, consonants paired with vowels will always designate a new syllable, and that greatly aids in the process of counting syllables in a name.
> "Bai" will produce *bye,* "Bao" will produce *bow.* 

However, this behavior is not consistent based on certain vowel combinations that are written in Chinese as two syllables:
>"Huaien" will produce *hoowhy-en,* "Sheer" will produce *shee-eer.*

Therefore it was important to address the concurrent vowels that appear in our data and label each with how many syllables they are, and that process is detailed in the later part of this report.
