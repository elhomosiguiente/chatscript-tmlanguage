##Control Token
```
#DO_DATE_MERGE
#DO_POSTAG
#DO_PARSE
#DO_CONDITIONAL_POSTAG
#NO_ERASE
#STRICT_CASING
#NO_INFER_QUESTION
#DO_SPELLCHECK
#ONLY_LOWERCASE
#NO_IMPERATIVE
#NO_WITHIN
#NO_SENTENCE_END
#NO_HYPHEN_END
#NO_COLON_END
#NO_SEMICOLON_END
#DO_ESSENTIALS
#DO_SUBSTITUTES
#DO_CONTRACTIONS
#DO_INTERJECTIONS
#DO_BRITISH
#DO_SPELLING
#DO_TEXTING
#DO_SUBSTITUTE_SYSTEM
#DO_INTERJECTION_SPLITTING
#DO_NUMBER_MERGE
#DO_PROPERNAME_MERGE
```

##System Variables
```
$cs_prepass 
$cs_control_pre 
$cs_control_main 
$cs_control_post 
$cs_token 
$cs_response 
$cs_crashmsg 
$cs_abstract 
$cs_userfactlimit 
$cs_randindex 
$$db_error 
$$findtext_start 
$$tcpopen_error 
$$document 
$cs_randindex 
$bot 
$login 
```

##Topic Fonctions  
```
^addtopic 
^available 
^cleartopics 
^counttopic 
^gambit 
^getrule 
^hasgambit 
^keep 
^lastused 
^next 
^poptopic 
^refine 
^rejoinder 
^respond 
^retry 
^reuse 
^setrejoinder  
^topicflags  
```

##Marking Functions  
```
^mark  
^unmark  
^marked 
^position 
^setposition 
```

##Input Functions  
```
^analyze 
^capitalized 
^input 
^position 
^removetokenflags 
^settokenflags 
^setwildcardindex 
```

##Number Functions
```
^compute 
^timefromseconds 
^timeinfofromseconds 
^timetoeconds 
```

##Output Functions
```
^flushoutput 
^insertprint 
^keephistory 
^lastsaid 
^print 
^preprint 
^repeat 
^reviseOutput 
```

##Output Access
```
^response 
^responsequestion 
^responseruleid 
```

##PostProcessing Functions
```
^postprintbefore 
^postprintafter 
```

##Control Flow Functions
```
^argument 
^command 
^end 
^eval 
^fail 
^match 
^nofail 
^notnull 
^addcontext 
^incontext 
```

##Word Manipulation Functions
```
^burst 
^explode 
^extract 
^findtext 
^flags 
^intersectwords 
^join 
^properties 
^pos 
^decodepos 
^partofspeech 
^role 
^tally 
^rhyme 
^substitute 
^spell 
^sexed 
^uppercase 
^addproperty 
^define 
^hasproperty 
^hasallproperty 
^hasanyproperty 
^properties 
^removeinternalflag 
^removeproperty 
^walkdictionary 
^Iterator 
```

##Multipurpose Functions
```
^disable 
^enable 
^length 
^pick 
^reset 
```

##Fact Functions
```
^FindFact 
^query 
^first 
^last 
^pick 
^sort 
^nth 
^Unpackfactref  
^AddProperty 
^conceptlist 
^Createattribute 
^createfact 
^revisefact 
^delete 
^field 
^find 
^Output 
^findmarkedfact 
^first 
^flushfacts 
^gambittopics 
^intersectfacts 
^keywordtopics 
^last 
^length 
^makereal 
^next 
^pendingtopics 
^pick 
^queryTopics 
^RemoveProperty 
^reset 
^query 
^save 
^sort 
^unduplicate 
^uniquefacts 
^unpackfactref 
```