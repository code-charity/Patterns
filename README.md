> ####  `thinking regularly, thinking universally, thinking mathematically`

# List of Patterns 🎇 'Pattern-Collector'   
The* ['awesome List'](https://github.com/sindresorhus/awesome#contents) of Patterns         \*_(there seems to be no other repo yet!)_  
Please edit this draft wildy 🎉 ( [Spreadsheet](https://docs.google.com/spreadsheets/d/1EjeZ2RtNpM_mANdO1VPXmZmbIb5vANUXodPBFtdg3zU/edit)  & [Readme](https://github.com/code4charity/PATTERNs--The-RegEx-Collector-queries-ontologies-sql-sparql-nosql-structured-unstructured-data/edit/main/README.md) ) <br> Patterns make bite-sized tools/co-work 🍒🍿🍟🤏 ( Searching such list (,once well filled,) you will already have mentally re-defined the specific regular scope of your goal (copying a specific pattern.) That can be more efficient and versatile than searching Stack Overflow Answers.  Or node.js NPM's (Instead of including a package you could often also copy&paste a regex).

## 1. **Reg**ular **Ex**pressions(=Search Patterns=Data format definitions.) 
Regex are most common & most efficient to type. (Despite they are one of the oldest dicsiplines in programming to make sense of data, convert it, clean it or spell-check it. https://en.wikipedia.org/wiki/Regular_expression)   
Regex are versatile, because they work in most languages and editors and many apps.
 
| Common Data Formats² | **match** | replacement | _comment/justify_ | extra³_ |
| --: | :-: | :--| --: | --: |
|ISBN ||
|Youtube Video ID |`[^\w-]([\w-]{11})[^\w-]`| $1 | 11char base64 is almost unique| `(?:https?://\|//)?(?:www\.\|m\.)?youtu/?be(?:\.com)?/(?:embed/\|v/\|watch\/?\?[&\w=]{,128}v=([\w-]{11})[^\w-]`| 
| **Hashes, Public Keys, Signatures** | **match** |  
| MD6 ||
| SHA256, Bitcoin, ... ||
| **Convert** | **match** | **replacement** |
|MarkDown links to HTML links | `\[([^\]]*)\]\(([^\)]*)\)`|`<a href="$2">$1</a>`|
|**this table**2Javascript |\\|\`([^\`]\*)\`\\\|\`([^\`]\*)\`\\||`replaceAll(/$1/g, "$2").replaceAll("\\|","\|")`| 
|Javascript 2 Python | _..._|_$1$2$3_|

*² date, postal code, formal greeting, formal __, ...* <br> _³extra: match typos too (common) and/or add precision ('no false positives' / perfectionism)_

[**we could add 1000s**]

## 1.1 Automatic pattern generation / AI

Currently little of this is automated. Solutions such as Microsoft Power Automate for Desktop (Windows 11) want to change some of it.

## 1.2 Pre-processing Patterns 
A raw text / data source material - or a list or category of patterns - can sometimes be analyzed for similarities and thus be combined in one preprocessing step. i.e. Preprocessing might Reduce Input data by 90% already in a fraction of the time / CPU

## 2. Contextual & Semantic patterns 
#### word-lists, topics, frequencies, thesaurus, antonyms,  semantic dictionaries, psychologic & sentiment dictionaries
wordnet, framenet, google ngrams, google trends, ....
#### Google Search: 
~synonyms a|b AROUND(3) c|d  -e|f|g|h|i|j|k|l|m|n|o|p|q|r|s|t|u|v|w|x|y|z    
https://ahrefs.com/blog/google-advanced-search-operators/
#### Human Grammar & Natural language processing (NLP):  
https://github.com/edobashira/speech-language-processing#readme

## 3. Structured Data. Querying Public Databases & the internet. SPARQL, SQL, NoSQL
#### Semantic web
#### WikiData
#### AWS public databases

## 4. Merging the above "1.-3."
### vs 5. Human work VS machine learning models

----

# All Patterns  
## https://docs.google.com/spreadsheets/d/1EjeZ2RtNpM_mANdO1VPXmZmbIb5vANUXodPBFtdg3zU/edit
- Others Lists  // potential Sources: ___ , ___ , ___ , ____ ,____ , ( not a list but 1 repo per regex: [https://github.com/regexhq](github/regexhq), takes clicks to see one: [regexhq/youtube-regex/index.js](https://github.com/regexhq/youtube-regex/blob/master/index.js))

- Compare:  https://www.mulesoft.com/exchange/?type=connector&view=list   (>10000 'enterprise converts')

| Name | **pattern match** | replacement | language | comment/justify | raw³ | extra context/precision |
| --: | :-: | :--|  --: |  --: |  --: |  --: |
| | | | regex |
| | | | google | 
| | | | css |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |



