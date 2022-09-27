# Andrey Nagumanov

### Junior Frontend Developer

-- --

### Contact information:
**Phone number:** +420-774-868-601  
**Address:** Štěpánská, 317/3, 60200, Brno, CZ  
**Email address:** vonamugan@gmail.com  
[GitHub](https://github.com/Vonamugan)  
[LinkedIn](https://www.linkedin.com/in/andrey-nagumanov/)  

-- --

### About myself:
Andrey is an engineer and a developer based in Brno with a passion for building digital services/stuff he wants.  
He is interested in all things launching products, from planning and design to solving real problems with code.  
If you too are trying to build something great, something that matters, let's get in contact via e.g. [LinkedIn](https://www.linkedin.com/in/andrey-nagumanov/).

-- --
### Bio:

- **1998** Born in Mykolaiv (Никола́ев), Ukraine.  
- **2019** Completed the Bachelor's Program in the Kazan National Research Technical University named after A.N.Tupolev (Казанский национальный исследовательский технический университет имени А. Н. Туполева)  
- **2019** Worked at Implant LLC. (Medical Devices)  
- **2021 to present** Compliting the Master's Program in the Brno University of Technology (Vysoké učení technické v Brně)  
-- --
### Education:

- 2021-Current
:   **Master, Bioengineering**; Brno University of Technology

- 2015-2019
:   **Bachelor , Jet Engines And Power Plants**; Kazan National Research Technical University named after A.N.Tupolev

-- --
### Work Experience:

- 2019-2022
  :   **Sr. Design Engineer** at Implant LLC., Kazan  
  *Main activities and responsibilities: Сreating solutions for the treatment of musculoskeletal system diseases,
  developing individual devices and complex systems of osteosynthesis in
  traumatology, and for the treatment of congenital pathologies.*

- 2017-2017
  :   **Sales manager** at YD, Kazan  
  *Main activities and responsibilities: Managed order cycle to enhance business development and maintain
  sustainability and customer satisfaction.*  

-- --
### Language skills:
- **Mother tongues:** Ukrainian, Russian
- **Other languages:** Czech(B2), English(B2)
-- --
### Digital skills:
- **Programming** Python, NodeJS, Bash, Git
- **Analytics** IPython, SQL, Matlab, DataStudio
- **Web/Media** React, Blender, Flask, HTML, CSS, JS
- **Engineering** SolidWorks, AutoCad, Fusion360, Geomagic, ANSYS, NX
-- --

### Code example:

![CodewarsBadge](https://www.codewars.com/users/Vonamugan/badges/small)  
**Sum of Digits / Digital Root** KATA from CODEWARS:   
*Digital root is the recursive sum of all the digits in a number.  
Given n, take the sum of the digits of n. If that value has more than one digit, continue reducing in this way until a single-digit number is produced. The input will be a non-negative integer.*
```
export const digitalRoot = (n:number):number => {
  let result = 0;
  String(n).split('').map(num => {
    result += Number(num);
  });
  return result >= 10 ? digitalRoot(result) : result;
};
```
-- --
