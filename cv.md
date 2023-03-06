# Anastasiya Klevko
---

## CONTACTS 

Phone: +37529 856-31-83  
E-mail: klevko.nastya@gmail.com  
GitHub: NotAnastasiya  
Discord rs-school: Anastasiya(@NotAnastasiya) 
---

## SUMMARY
### Each new experience is a great opportunity to learn new skills or improve existing ones. Technical education gave me a wide range of new knowledge in various fields, taught me to approach the solution of a problem step by step, analyzing it and compiling a solution algorithm. My current experience as a sales manager has helped me develop skills such as multitasking and communication skills that will help me in my new profession.

---


## WORK EXPERIENCE
Sales Manager (2018-present time)

## EDUCATION
Belarusian National Technical University, engineer (2013-2018)
---


## SKILLS
- HTML: basic
- CSS: basic
- JavaScript: basic
- Git: basic

## CODE EXAMPLE
Implement the function which takes an array containing the names of people that like an item. It must return the display text as shown in the examples:
![task](task.jpeg "task_codewars")
```
function likes(names) {
  let result = [...names];
  if (result.length < 2) {
    result.push('no one');
    return `${result[0]} likes this`;
  }
  if (result.length > 2) {
    let newArr = [];
    for ( ;newArr.length < 2 ;){
      let item = result.shift()
      newArr.push(item);
    }
    if (result.length > 1) {
      result.unshift(`${result.length} others`);
    }
    result.unshift(newArr.join(', '));  
  }
  return `${result[0]} and ${result[1]} like this`;
  console.log([].length)
}
```
---

## COURSES 
JavaScript/Front-end Pre-School 2022Q4 ([RS School](https://rs.school/ "RS")) [certificate](https://app.rs.school/certificate/ajmq2cqd "certificate")
Computer Science Basics ([EPAM](https://learn.epam.com/ "EPAM"))  
Software Development Methodologies ([EPAM](https://learn.epam.com/ "EPAM"))   
Introduction to Testing ([EPAM](https://learn.epam.com/ "EPAM"))   

## LANGUAGES 
English - A2