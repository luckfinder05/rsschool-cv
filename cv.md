# Vladislav Novitskiy

## Contact Information
e-mail: no-vlad@yandex.ru

telegram: @no_vlad

github: https://github.com/luckfinder05

## Brief Self-Introduction
I'm a beginner web-developer without work experience and my goal is to get some experience by completing projects in the rs-school.

I've learned by myself html, css, javascript, after what I understood that I need backend knowledge and learned expressjs.

<img src="https://github.com/luckfinder05/rsschool-cv/assets/39525356/27614c92-c681-4cef-bdae-5f919f6b6281"
height="400"
width="400"
  style="text-align:center;"
  />

## Skills
Web-development: HTML5, CSS3, Javascript

Frameworks: React, Nextjs

Version control: GIT, Github

Graphics: Figma

## Code Examples
```js
Array.prototype.sameStructureAs = function (other) {
  
  function checkArrays(arr1,arr2){
    if (isArray(arr1)!==isArray(arr2) || (isArray(arr1) && arr1.length!==arr2.length)) return false;

    const result =  arr1.reduce((state,item,index)=>{
      if (!isArray(item) && !isArray(arr2[index])) return state && true;      
      if (isArray(item) && isArray(item) && isArray(arr2[index])) return state && checkArrays(item, arr2[index]);
      return state && false;
    },true)
    return result
  }
  
  return checkArrays(this,other);
};
```

## Work Experience
Have no finished project I can be proud of.

## Education (including completed courses and training)
Udemy Web-developer 2021

## English Language (your English proficiency level, and if you had language practice, describe it)
My English proficiency level is B2. I've had practice in 2018 while constructing solar station.
