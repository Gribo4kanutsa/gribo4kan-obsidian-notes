```dataviewjs
const currentHour = moment().format('HH');
console.log(currentHour)
let greeting;
if (currentHour >= 18 || currentHour < 23) {
 greeting = 'Good evening'
} else if (currentHour >= 8 && currentHour < 12) {
greeting = 'Good morning'
} else if (currentHour >= 12 && currentHour < 18) {
greeting = 'Good afternoon'
} else {
greeting = 'Good night'
}
  
dv.header(1, greeting)
```

В разделе 