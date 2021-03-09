# Aleksey Budanov

### Contacts 
  - +375291591108
  - budanov.info@gmail.com
  - budanov.info - skype 

### Summary

Start a career of Junior Front-end developer with primary skill in JavaScript, gain practical experience and knowledge, learn new technologies and frameworks. Get real project experience and development skills. Become a team lead in 5 years. Full-time employment. Ready to relocate.

### Skills

   ##### Front-end
   ###
    HTML 5 / CSS 3 / JavaScript / JQuery
    React / Redux
   ##### Back-end
   ###
    node.js 
   ##### Architecture
   ###
    Networks, protocols
   ##### Domains
   ###
    Games as SPA 
   ##### Tools
   ###
    Webpack
    Git
  ##### Light touch
  ###
    Cloud : AWS (EC2)
    Virtualization: Vagrant



### Code examples
##### Testing React App
### 
```javascript
import React from 'react';
import { shallow } from 'enzyme';
import { expect } from 'chai';

import PageNotFound from '../../../../client/components/common/page_not_found';

describe('<PageNotFound />', function() {
  it('contains "Page not found" message', function() {
    const wrapper = shallow(<PageNotFound />);
    expect(wrapper.text()).to.contain('Page not found');
  });
});

```
#### Love Triangles
```javascript
module.exports = function getLoveTrianglesCount(preferences = []) {
var arr = [...preferences]
 if(arr.length < 3) return 0;
 var answer = 0;
 var alreadyInLove = [];
 arr.forEach((item, index) => {
  var n = alreadyInLove.includes(index);
  if(!n) {
   var secondLoveIndex = item - 1;
   if(secondLoveIndex != index) {
    var secondLoveItem = arr[secondLoveIndex];
    if(secondLoveItem) {
     var thirdLoveIndex = secondLoveItem - 1;
     if(thirdLoveIndex != secondLoveIndex && thirdLoveIndex != index) {
      var thirdLoveItem = arr[thirdLoveIndex];
      if(thirdLoveItem) {
       if((thirdLoveItem - 1) === index) {
        answer++;
        alreadyInLove = [...alreadyInLove, index, secondLoveIndex, thirdLoveIndex];
       }
      }
     }
    }
   }
  } 
 });
 return answer;
};
```

### Experience
 - ##### Front-end developer – MageWorx;
 - ##### Front-end internship – IBA;
- ##### alekseyminsk.github.io/Space-odyssey – game, based on Phaser;
- ##### alekseyminsk.github.io/Match-Match-Game/index.html – game, based on pure Java Script;

### Education 
  ###### Belarusian National Technical University, Minsk 
  - Bachelor of Retail Store Equipment Technologies - engineer, January 2018
### English skill
 - Intermediate level
 