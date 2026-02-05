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