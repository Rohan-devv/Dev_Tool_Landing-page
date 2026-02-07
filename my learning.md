20px ka kya matlab?
margin-top: 20px;
margin-bottom: 20px;


✔️ Element ke upar aur neeche 20px ka gap

🔹 auto ka kya matlab?

This is the magic part 🪄

margin-left: auto;
margin-right: auto;


👉 Browser left aur right ka space automatically calculate karta hai
👉 Result: element horizontally center ho jaata hai

🔹 MOST IMPORTANT RULE ⚠️

margin: auto tabhi kaam karega jab:

✔️ Element ka width defined ho
✔️ Element block-level ho

div {
  width: 300px;
  margin: 20px auto;
}


✅ CENTER ho jayega

❌ Without width:

div {
  margin: 20px auto;
}


➡️ NO CENTERING (kyunki width = 100%)

# Learning No--> 2

// jab grid use kar rahe ho to fraction equally adjust karr lenge card ke height and weight ki tension lene ki jrurat nahi ahi 

### Learning -->3
Important rule remember forever

To stick element to bottom inside card:

parent → display:flex
parent → flex-direction:column
child → margin-top:auto

Why your current align-items:fl


# Footer learning
jab display grid laagao to align item start krne se pehla element top se hi start hoga!!

# Card learning 
dekh koi bhi content upar top pe hota hai and loi bottom hota hai to bss to dono ko alg div me rakhh flex laga column wise or neeche wale content ka margin-top:auto krna hota hai bss 
