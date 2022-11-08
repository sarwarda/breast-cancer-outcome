{\rtf1\ansi\ansicpg1252\cocoartf2706
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica-Bold;\f1\fswiss\fcharset0 Helvetica;\f2\fnil\fcharset0 Menlo-Regular;
\f3\fswiss\fcharset0 Helvetica-Oblique;\f4\fnil\fcharset0 HelveticaNeue;}
{\colortbl;\red255\green255\blue255;\red0\green0\blue0;\red255\green255\blue255;\red0\green0\blue0;
}
{\*\expandedcolortbl;;\cssrgb\c0\c0\c0\c87059;\cssrgb\c100000\c100000\c100000\c0;\cssrgb\c0\c1\c1;
}
{\*\listtable{\list\listtemplateid1\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid1\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{hyphen\}}{\leveltext\leveltemplateid2\'01\uc0\u8259 ;}{\levelnumbers;}\fi-360\li1440\lin1440 }{\listname ;}\listid1}
{\list\listtemplateid2\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid101\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{hyphen\}}{\leveltext\leveltemplateid102\'01\uc0\u8259 ;}{\levelnumbers;}\fi-360\li1440\lin1440 }{\listname ;}\listid2}}
{\*\listoverridetable{\listoverride\listid1\listoverridecount0\ls1}{\listoverride\listid2\listoverridecount0\ls2}}
\margl1440\margr1440\vieww11520\viewh12960\viewkind0
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0

\f0\b\fs24 \cf0 Read Me\

\f1\b0 \

\f0\b Project Contents\

\f1\b0 \
\pard\tx220\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\li720\fi-720\pardirnatural\partightenfactor0
\ls1\ilvl0\cf0 {\listtext	\uc0\u8226 	}Jupyter Notebooks\
\pard\tx940\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\li1440\fi-1440\pardirnatural\partightenfactor0
\ls1\ilvl1\cf0 {\listtext	\uc0\u8259 	}ETL and EDA notebook in .ipynb format\
{\listtext	\uc0\u8259 	}Classification notebook in .ipynb format\
{\listtext	\uc0\u8259 	}Original, cleaned, and pre-proccessed datasets (categorical variable encodings)\
{\listtext	\uc0\u8259 	}graphviz decision tree visualization (.png)\
{\listtext	\uc0\u8259 	}graphviz dot file for decision tree\
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0
\cf0 \
\pard\tx220\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\li720\fi-720\pardirnatural\partightenfactor0
\ls2\ilvl0\cf0 {\listtext	\uc0\u8226 	}Tableau Data Files\
\pard\tx940\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\li1440\fi-1440\pardirnatural\partightenfactor0
\ls2\ilvl1\cf0 {\listtext	\uc0\u8259 	}Exploration of Breast Cancer Mortality files (.twb and .twbx)\
{\listtext	\uc0\u8259 	}SEER Breast Cancer Decision Tree tableau files (.twb and .twbx)\
{\listtext	\uc0\u8259 	}Decision Tree tableau excel file, which includes data used to manually build the tree in tableau\
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0
\cf0 \
All necessary imports for python environment are listed at the top of each notebook. To reiterate, the necessary python version and libraries used in the notebook includes:\
\
` ` `\
\pard\pardeftab720\partightenfactor0

\f2\fs26 \cf2 \cb3 \expnd0\expndtw0\kerning0
Python 3.9.10\
\
numpy\
random \
seaborn \
matplotlib.pyplot\
pandas\
scipy.stats\
graphviz\
sklearn\
pydotplus\
IPython
\f1\fs24 \cf0 \cb1 \kerning1\expnd0\expndtw0 \
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0

\f3\i \cf0 \
` ` `\
\
Notebooks are already cleanly executed for ease of review. \
\
\
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0

\f0\i0\b \cf0 Dataset Link:
\f3\i\b0 \
\
\pard\pardeftab720\sa280\partightenfactor0

\f4\i0 \cf4 \cb3 \expnd0\expndtw0\kerning0
https://ieee-dataport.org/open-access/seer-breast-cancer-data
\f1 \cf0 \cb1 \kerning1\expnd0\expndtw0 \
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0
\cf0 \

\f0\b Tableau Public Links:
\f1\b0 \
\
https://public.tableau.com/views/ExplorationofBreastCancerMortality/ExplorationofSEERBreastCancerDataset?:language=en-US&:display_count=n&:origin=viz_share_link\
\
https://public.tableau.com/views/DecisionTreeClassifierforBreastCancerMortality/DecisionTreeClassifierforSEERBreastCancerData?:language=en-US&:display_count=n&:origin=viz_share_link\
\
}