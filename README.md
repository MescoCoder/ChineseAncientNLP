# ChineseAncientNLP
The dataset of QSL-Corpus is annotated based on the book of Qingshilu for the task of relation extraction. Another publich dataset is C-CLUE (see more in the url of https://github.com/jizijing/C-CLUE). The format of each dataset is based on "JSON", in which a complete annotated segment is in a line like the following:<br>
{  "text": "以故等阿思哈尼哈番硕色子常禄，袭职 ", <br>
   "spo_list": {<br>
       "subject": "常禄", <br>
        "object": "阿思哈尼哈番", <br>
        "subject_type": "peop", <br>
        "object_type": "offi", <br>
        "predicate": "任职"<br>
   }<br>
}<br>
.....<br>

The meaning of metadata: <br>
text: the raw sentence;<br>
spo_list: the triplet including the detail for the subject, object and predicate in the sentence;<br>
xxx_type: the type of xxx, such as subject_type representing which type of entities the subject belongs to.<br>
