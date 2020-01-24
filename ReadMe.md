{\rtf1\ansi\ansicpg1252\cocoartf1504\cocoasubrtf840
{\fonttbl\f0\fnil\fcharset0 HelveticaNeue-Medium;\f1\fnil\fcharset0 HelveticaNeue;}
{\colortbl;\red255\green255\blue255;\red27\green31\blue34;\red255\green255\blue255;\red10\green77\blue204;
}
{\*\expandedcolortbl;;\cssrgb\c14118\c16078\c18039;\cssrgb\c100000\c100000\c100000;\cssrgb\c1176\c40000\c83922;
}
{\*\listtable{\list\listtemplateid1\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid1\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid1}
{\list\listtemplateid2\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid101\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid2}
{\list\listtemplateid3\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid201\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid3}}
{\*\listoverridetable{\listoverride\listid1\listoverridecount0\ls1}{\listoverride\listid2\listoverridecount0\ls2}{\listoverride\listid3\listoverridecount0\ls3}}
\paperw11900\paperh16840\margl1440\margr1440\vieww25400\viewh14500\viewkind0
\deftab720
\pard\pardeftab720\sl600\sa320\partightenfactor0

\f0\b\fs48 \cf2 \cb3 \expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Recommendations Engines with IBM\
\pard\pardeftab720\sl360\sa320\partightenfactor0

\f1\b0\fs32 \cf2 This project was designed to analyze the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles.\
\pard\pardeftab720\sl360\partightenfactor0

\f0\b\fs36 \cf4 \cb1 \strokec4 \
\pard\pardeftab720\sl440\sa320\partightenfactor0
\cf2 \cb3 \strokec2 Installations\
\pard\pardeftab720\sl360\sa320\partightenfactor0

\f1\b0\fs32 \cf2 This project requires Python 3.x and the following Python libraries installed:\
\pard\tx220\tx720\pardeftab720\li720\fi-720\sl360\partightenfactor0
\ls1\ilvl0\cf4 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\'95	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec4 NumPy\cf2 \cb1 \strokec2 \
\ls1\ilvl0\cf4 \cb3 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\'95	}{\field{\*\fldinst{HYPERLINK "http://pandas.pydata.org/"}}{\fldrslt \expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec4 Pandas}}\cf2 \cb1 \expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 \
\ls1\ilvl0\cf4 \cb3 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\'95	}{\field{\*\fldinst{HYPERLINK "http://scikit-learn.org/stable/"}}{\fldrslt \expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec4 scikit-learn}}\cf2 \cb1 \expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 \
\pard\pardeftab720\sl360\partightenfactor0

\f0\b\fs36 \cf4 \strokec4 \
\pard\pardeftab720\sl440\sa320\partightenfactor0
\cf2 \cb3 \strokec2 Summary:\
\pard\pardeftab720\sl360\sa320\partightenfactor0

\f1\b0\fs32 \cf2 The project contains the following tasks:\
\pard\tx220\tx720\pardeftab720\li720\fi-720\sl360\partightenfactor0
\ls2\ilvl0\cf2 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\'95	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Exploratory Data Analysis: This part is for data exploration.\cb1 \
\ls2\ilvl0\cb3 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\'95	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Rank Based Recommendations: To get started in building recommendations, I first find the most popular articles based on the most interactions. These are then the articles we might recommend to new users (or anyone depending on what we know about them).\cb1 \
\ls2\ilvl0\cb3 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\'95	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 User-User Based Collaborative Filtering: In order to build better recommendations for the users of IBM's platform, I look at users that are similar in terms of the items they have interacted with. These items could then be recommended to similar users.\cb1 \
\ls2\ilvl0\cb3 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\'95	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Content Based Recommendations: Using NLP skills, I developed a content-based recommendation system.\cb1 \
\ls2\ilvl0\cb3 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\'95	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Matrix Factorization: Finally, I completed a machine learning approach to building recommendations. Using the user-item interactions, I built out a matrix decomposition. Using the decomposition, I got an idea of how well I can predict new articles an individual might interact with .\cb1 \
\pard\pardeftab720\sl360\partightenfactor0

\f0\b\fs36 \cf4 \strokec4 \
\pard\pardeftab720\sl440\sa320\partightenfactor0
\cf2 \cb3 \strokec2 Data\
\pard\tx220\tx720\pardeftab720\li720\fi-720\sl360\partightenfactor0
\ls3\ilvl0
\f1\b0\fs32 \cf2 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\'95	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 user-item-interactions.csv: file contains user interaction.\cb1 \
\ls3\ilvl0\cb3 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\'95	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 articles_community.csv: file contains articles description.\cb1 \
\pard\pardeftab720\sl360\partightenfactor0

\f0\b\fs36 \cf4 \strokec4 \
\pard\pardeftab720\sl440\sa320\partightenfactor0
\cf2 \cb3 \strokec2 Acknowledgments\
\pard\pardeftab720\sl360\partightenfactor0

\f1\b0\fs32 \cf2 I would like to thank\'a0{\field{\*\fldinst{HYPERLINK "https://eu.udacity.com/"}}{\fldrslt \cf4 \strokec4 Udacity}}\'a0for this amazing project, and\'a0{\field{\*\fldinst{HYPERLINK "https://dataplatform.cloud.ibm.com/"}}{\fldrslt \cf4 \strokec4 IBM}}\'a0for providing the data.\
}