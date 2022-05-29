# Tibetan script and language development

## Language development

```{mermaid}
graph TD;  
subgraph languages
A[Happaran language];  
C[Elamo-Dravidian languages]-->D[Elamite];
C-->E[Dravidian];

AH[Afro-Asiatic language family]-->AI[Semitic];
AI-->AJ[East Semitic];
AJ-->AK[Akkadian];
AI-->AM[Central Semitic];
AM-->AN[Northwest Semitic];
AN-->AO[Aramaic];
AO-->AP[Eastern Aramaic];
AP-->AQ[Northeastern Neo-Aramaic];
AQ-->AR[Assurian];

AA[Indo-European language family]-->AB[Indo-Iranian];
AB-->AC[Indo-Aryan];
AC-->AD[Sanskrit];

BE[Sumerian language - isolate]<-.->AK;

AAA[Sino-Tibetan]-->AAB[Tibeto-Kanauri]
AAB-->AAC[Bodish]
AAC-->AAD[Tibetic]
AAD-->AAE[Old Tibetan]
AAE-->AAF[Tibetan]

AAA-->AAG[Sinitic]
AAG-->AAH[Chinese]
end
```
Source: compiled from Wikipedia 2022-05
## Script development

```{mermaid}
graph TD;  
subgraph scripts
BA(Megalithic graffiti symbols?)-.->BB(Indus script 3500 BC - 1900 BC);


CA(Linear Elamite script 2300 BC - 1850 BC);
CA-->CB(Cuneiform Elamite);
CB-->CD(Cuneiform Sumerian);
CD-->CE(Cuneiform Arcadian);

L0A(Egyptian Hieroglyphs 3200 BC - AD 400)-->LA
LA(Proto-Sinaitic script 1900 BC - 1500 BC)-->LB(Phoenician alphabet 1050 BC - 150 BC)
LB-->LC(Aramaic alphabet 800 BC - AD 600)
LC-->LD(Brāhmī 300 BC - AD 500)
LD-->LE(Gupta)
LE-->LF(Siddhaṃ)
LF-->LG(Nāgarī)
LG-->LH(Devanagari)
LH-->LI(Tibetan script)

LA-->LK(Greek alphabet 800 BC - present)
LK-->LL(Old Italic script 700 BC - 100 BC)
LL-->LM(Latin alphabet 700 BC - present)

BB-.->LD;
BB-.->BA;
BB-.->CA;

end
```
Source: compiled from Wikipedia 2022-05

<!--
-.->LI;

A<-.->BB
AK<-.->CE;
LD<-.->AD;
LH<-.->AD;
BE-.->AK;
BE<-.->CD;

D<-.->CA;
AN<-.->LA;
AAF<
-->