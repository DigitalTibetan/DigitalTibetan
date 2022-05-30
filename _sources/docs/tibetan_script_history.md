# A schematic overview of the history of Tibetan script and language development

While Tibetan script is (remotely) related to Western Latin script, the Tibetan language is part of the Sino-Tibetan language family, without common ancestor with Indo-European or Afro-Asiatic languages. The following is a short overview of the relations between different scripts and languages:
## Script development

The following table compares five consonants in different scripts. With exception of Proto-Sinaitic, Gupta, and Nāgarī all display requires the corresponding Unicode fonts being installed.

|language | b | d | m | r | t |
| :- | - | - | - | - | - |
|Hieroglyphic | 𓉐  | 𓉿  | 𓈖  | 𓁶 | 𓏴 |
|Proto-Sinaitic[^proto_sinaitic] | <img src="Images/ProtoSinaitic-b.jpg" width="16px" /> | <img src="Images/ProtoSinaitic-d.jpg" width="16px" /> | <img src="Images/ProtoSinaitic-m.jpg" width="16px" /> | <img src="Images/ProtoSinaitic-r.jpg" width="16px" /> | <img src="Images/ProtoSinaitic-t.jpg" width="16px" /> |
|Phoenician | 𐤁 | 𐤃 | 𐤌 | 𐤓 | 𐤕 |
| Aramaic | 𐡁 | 𐡃 | 𐡌 | 𐡓 | 𐡕 |
| Brāhmī | 𑀩 | 𑀤 | 𑀫 | 𑀭 | 𑀢 |
| Gupta[^gupta] | <img src="Images/Gupta_b.jpg" width="10px" /> | <img src="Images/Gupta_d.jpg" width="10px" /> | <img src="Images/Gupta_m.jpg" width="10px" /> | <img src="Images/Gupta_r.jpg" width="10px" /> | <img src="Images/Gupta_t.jpg" width="10px" /> | 
| Siddhaṃ | 𑖤 | 𑖟 | 𑖦 | 𑖨 | 𑖝 |
| Nāgarī[^nagari] | <img src="Images/Nagari_b.jpg" width="12px" /> | <img src="Images/Nagari_d.jpg" width="12px" /> | <img src="Images/Nagari_m.jpg" width="12px" /> | <img src="Images/Nagari_r.jpg" width="12px" /> | <img src="Images/Nagari_t.jpg" width="12px" /> |
| Devanagari | ब | द | म | र | त |
| Tibetan | བ | ད | མ | ར | ཏ |

|language | b | d | m | r | t |
| :- | - | - | - | - | - |
|Hieroglyphic | 𓉐  | 𓉿  | 𓈖  | 𓁶 | 𓏴 |
|Proto-Sinaitic[^proto_sinaitic] | <img src="Images/ProtoSinaitic-b.jpg" width="16px" /> | <img src="Images/ProtoSinaitic-d.jpg" width="16px" /> | <img src="Images/ProtoSinaitic-m.jpg" width="16px" /> | <img src="Images/ProtoSinaitic-r.jpg" width="16px" /> | <img src="Images/ProtoSinaitic-t.jpg" width="16px" /> |
| Greek | Β | Δ | Μ | Ρ | Τ |
| Old Italic | 𐌁 | 𐌃 | 𐌌 | 𐌓 | 𐌕 |
| Latin | B | D | M | R | T |

[^proto_sinaitic]: Not yet (2022-05) part of Unicode, glyphs from: <https://omniglot.com/writing/protosinaitc.htm>
[^gupta]: Not yet (2022-05) part of Unicode, glyphs from: <https://en.wikipedia.org/wiki/Gupta_script> by: <https://commons.wikimedia.org/wiki/User:Mhss>
[^nagari]: Not part of Unicode, considered variant of Devanagari, glyphs from <https://en.wikipedia.org/wiki/N%C4%81gar%C4%AB_script> by: <https://commons.wikimedia.org/w/index.php?title=User:Benedettou&action=edit&redlink=1>

```{mermaid}
graph TD;  
BA(Megalithic graffiti symbols)-.->BB(Indus script 3500 BC - 1900 BC);

CA(Linear Elamite script 2300 BC - 1850 BC)-->CB(Cuneiform Elamite);
CB-->CD(Cuneiform Sumerian);
CD-->CE(Cuneiform Arcadian);
L0A(Egyptian Hieroglyphs 3200 BC - AD 400<br>)-->LA(Proto-Sinaitic script 1900 BC - 1500 BC);
LA-->LB(Phoenician alphabet 1050 BC - 150 BC);
LB-->LC(Aramaic alphabet 800 BC - AD 600);
LC-->LD(Brāhmī 300 BC - AD 500);
LD-->LE(Gupta);
LE-->LF(Siddhaṃ);
LF-->LG(Nāgarī);
LG-->LH(Devanagari);
LH-->LI(Tibetan script);
LA-->LK(Greek alphabet 800 BC - present);
LK-->LL(Old Italic script 700 BC - 100 BC);
LL-->LM(Latin alphabet 700 BC - present);
BB-.->LD;
BB-.->BA;
BB-.->CA;
```
Source: compiled from Wikipedia 2022-05

## Language development

```{mermaid}
graph TD;
AAA[Sino-Tibetan language family]-->AAB[Tibeto-Kanauri];
AAB-->AAC[Bodish];
AAC-->AAD[Tibetic];
AAD-->AAE[Old Tibetan];
AAE-->AAF[Tibetan];
AAA-->AAG[Sinitic];
AAG-->AAH[Chinese];
```

```{mermaid}
graph TD;
AA[Indo-European language family]-->AB[Indo-Iranian];
AB-->AC[Indo-Aryan];
AC-->AD[Sanskrit];
AA-->ABA[Germanic];
ABA-->ABB[West Germanic];
ABB-->ABC[High German];
ABC-->ABD[German];
ABB--> ABBA[North Sea Germanic];
ABBA-->ABBB[Anglo-Frisian];
ABBB-->ABBC[Anglic];
ABBC-->ABBD[English];
AA-->ACA[Italo-Celtic?];
ACA-->ACB[Italic];
ACB-->ACC[Romance];
ACC-->ACD[Western Romance];
ACD-->ACE[Gallo-Romance];
ACE-->ACF[Oïl];
ACF-->ACG[French];
```

```{mermaid}
graph TD;  
AH[Afro-Asiatic language family]-->AI[Semitic];
AI-->AJ[East Semitic];
AJ-->AK[Akkadian];
BE[Sumerian language isolate]<-.->AK;
AI-->AM[Central Semitic];
AM-->AN[Northwest Semitic];
AN-->AO[Aramaic];
AO-->AP[Eastern Aramaic];
AP-->AQ[Northeastern Neo-Aramaic];
AQ-->AR[Assurian];
```
Sources: compiled from Wikipedia 2022-05
