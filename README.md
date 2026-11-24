// Q1. Create a JSON Object
let student1 = {
    name: "Arun",
    age: 25,
    department: "IT"
};
console.log(student1);


// Q2. Access JSON Properties
let student2 = {
    name: "Priya",
    age: 22,
    city: "Bangalore"
};
console.log(student2.name);
console.log(student2.city);


// Q3. Convert JSON into JavaScript Object
let student = '{"name":"Ravi","age":24}';
let obj = JSON.parse(student);
console.log(obj.name);


// Q4. Convert JavaScript Object into JSON
let student3 = {
    name: "Arun",
    age: 25,
    city: "Bangalore"
};
let jsonString = JSON.stringify(student3);
console.log(jsonString);


// Q5. Create a Simple XML Document
let xml = `
<student>
    <name>Kumar</name>
    <age>23</age>
    <department>CSE</department>
</student>
`;
