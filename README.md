# ChineseAncientNLP
The dataset of QSL-Corpus is annotated based on the book of Qingshilu for the task of relation extraction. Another publich dataset is C-CLUE (see more in the url of ). The format of each dataset is based on "JSON", in which a complete annotated segment is in a line like the following:
{  "text": "以故等阿思哈尼哈番硕色子常禄，袭职 ", 
   "spo_list": {
       "subject": "常禄", 
        "object": "阿思哈尼哈番", 
        "subject_type": "peop", 
        "object_type": "offi", 
        "predicate": "任职"
   }
}
.....

The meaning of metadata: 
text: the raw sentence;
spo_list: the triplet including the detail for the subject, object and predicate in the sentence;
xxx_type: the type of xxx, such as subject_type representing which type of entities the subject belongs to.
