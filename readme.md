
### 6. Answer the following questions clearly:

1. What is the difference between **getElementById, getElementsByClassName, and querySelector / querySelectorAll**?
Ans: getElementByID এটা দিয়ে সুধু ID এলিমেন্ট গুলাকে খুজে নিয়ে আসে।।যেহেতু Id একটি ইউনিক হয় তাই এলিমেন্ট গুলোকে খুজে নিয়ে আসা সুবিধা হয়।

getElementByClassName: এটা class name দিয়ে এলিমেন্ট খুজে আনে, যেহাতু আমরা একই class বিভিন্ন জায়গায় ব্যবহার করতে পারি তাই এটা একটা list ht,l(Collection) তৈরি করবে।

quarySelector: এটা দিয়ে CSS এর selector ব্যবহার করে এলিমেন্ট খুজে আনে।

quarySelectorAll: এটাও অনেকটা quarySelector এর মতো কিন্তু সব matching এলিমেন্ট গুলোকে নিয়ে আসে।

2. How do you **create and insert a new element into the DOM**?
Ans: প্রথমে আমরা একটা এলিমেন্ট তৈরি করি এর পর contant যোগ দেই তারপর class বা ID যোগ দেই এরপর DOM ব্যবহার করি।। DOM ব্যবহার করে HTML এর ভিতরে অনেক Contant change করতে পারি।।

3. What is **Event Bubbling** and how does it work?
Ans : Event Bubbling: amra jokhon ekta parant div er vetore onek gulo choto choto child div rakhi and oi child div er vitore aro child div rakhi ba contant rakhi..so amra jokhon event e kono "click" call kori tokhon seta element e jeye theme jay na...se prottekta parrent ke dhorte thake..jotokhon projonto parant div sesh na hocche totokhon..eyvabe "Event Bubbling" cholte thake..

4. What is **Event Delegation** in JavaScript? Why is it useful?
Ans: Event Delegation diye amra child element e event listenr bebohar na kore tar parant element e event listener bosay kaj korte pari ete code kom lekha hoy and performance valo hoi, dynamic vabe bebohar korte pari
5. What is the difference between **preventDefault() and stopPropagation()** methods?

Ans: preventDefault er kaj holo kono default behavior bondho kora ba browser er default vabe jeno kaj na kore seta ke bondho kora.

stopPropagation: er kaj holo event bubbling ba capturing bondho kora.

---


