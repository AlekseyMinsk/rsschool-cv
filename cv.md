# Aleksey Budanov

### Contact Info
  - budanov.info@gmail.com

### Summary
Self-motivated and experienced Web Applications developer with deep knowledge of modern Web Technologies and Agile methodologies. 
I gained development skills on real projects, courses and at university and prone to constant learning. I am eager to join a team as Front-end developer and
implement all my expertise to improve current processes along with taking the product to the next level.

### Skills
* ##### TypeScript
* ##### React / Redux
* ##### Angular
* ##### NodeJS
* ##### Docker
 
### Code examples

```javascript
const jwt = require('jsonwebtoken');
const { secret } = require('./config.js');

module.exports = (request, response, next) => {
  try {
    const tokenLocal = request.headers.authorization.split(' ')[1];
    const decodedData = jwt.verify(tokenLocal, secret);
    request.username = decodedData.username;
    next();
  } catch (e) {
    console.log(e);
    return response.status(400).json({message: 'Not authorized'})
  }
}
```

### Experience
* ##### Web Application Developer - ALDI Technology Hub, 11.2023 - current
* ##### Technical Support sprcialist -> Front-end developer – MageWorx, 12.2018 - 10.09.2023;
* ##### Front-end internship – IBA, 2018;

### Education
##### Belarusian National Technical University, Minsk 
* ##### Bachelor of Retail Store Equipment Technologies - engineer, January 2018

### English

* ##### B2 both communication and writing skills. Experience of working in an international team.
