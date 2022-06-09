# Artem Chabanovich

## Contacts
* Location: Warsaw, Poland
* Phone: +48 572 144 807
* Discord: Artem Chabanovich (@chaart13)
* Email: [chaart13@gmail.com](mailto:chaart13@gmail.com)
* GitHub: [chaart13](https://github.com/chaart13)
* LinkedIN: [Artem Chabanovich](https://www.linkedin.com/in/artem-chabanovich/)

## About Me
I have been starting learning programming for front-end a couple of times but haven't successeded yet. My friends were helping me, I took some free online courses but I didn't have a goal at that moment.
Currently I work as ABAP Developer at LeverX. As SAP is constantly developing, learning JS will definetely help me to lead my carier and participate in different new projects.  
Or I can just requalify instead.

## Skills
Mainly was focused on ABAP and other technologies connected to SAP world such as CDS, BOPF, RAP, CAP, OData. Also as I tried to explore front-end development on my own, I've got some knowledge in HTML, CSS (a bit Tailwind), JS and a bit React.

## Code example
"Duplicate Encoder" from [Codewars.](https://www.codewars.com/kata/54b42f9314d9229fd6000d9c/javascript)  
The goal of this exercise is to convert a string to a new string where each character in the new string is "(" if that character appears only once in the original string, or ")" if that character appears more than once in the original string. Ignore capitalization when determining if a character is a duplicate.
```javascript
function duplicateEncode(word){  
  let unique = {};  
  word = word.toLowerCase();
  
  for ( let i in word ) {
    unique[word[i]] = unique[word[i]] === undefined ? true : false;
  }

  return word.replace( /./g, (match) => unique[match] ? '(' : ')' )
}
```
## Experience
ECONOMIST-ANALYST, ALUTECH GROUP  
*Minsk, Belarus — February, 2018 – February, 2021*

Provided supply chain management in managing company of Alutech Group using products, such as SAP APO, SAP ERP and Microsoft Excel. 

Accomplishments:
*	Developed a tool for supply chain management based on Microsoft Excel (VBA), which allowed faster, clearer and more accurate management.
*	Automated daily reports on warehouse status based on data from SAP ERP.
*	Conducted training on the new procurement business process for employees of offices in Russia, Ukraine and Belarus.

ABAP DEVELOPER, LEVERX GROUP LLC  
*Minsk, Belarus — February, 2021 – present*

Carried out key developer responsibilities such as ABAP developing and testing, resolving technical issues. Participated in both developing new and supporting existing projects for S/4HANA.

Projects:
*	Development for SAP EAM module. Integrated new reusable S/4HANA output control to existing transactions, including gateway-based Adobe Forms, e-mail templates, CDS and OData service support and optimization. Created job scheduling applications, new authorization objects to existing applications. Implemented new RAP based application. Unit and integration testing. 
*	CPI Support for greenfield CAP based application. Provided client support, fixed incoming issues.

## Education
BACHELOR IN ECONOMIC CYBERNETICS    
*Belarussian State Economic University — 2012-2018*

*	Mathematical methods and models in economics
*	Econometrics
*	Multivariate statistical analysis

COURSE “MODERN SAP DEVELOPMENT”  
*EPAM Systems — 2019-2020*

Leaned the basics of Core ABAP, CDS Views, BOPF, SAP ERP (overview)

## Language
* English - Upper Intermediate
* Polish - Intermediate
* Russian - Native
