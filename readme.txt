My CSS Learnings	



VIDEO 6 - Static, Relative, Absolute, Fixed, Sticky

CSS mein position property kisi element ki location ko control karti hai. Iske 5 main values hoti hain: static, relative, absolute, fixed, aur sticky. Inko ek-ek karke samajhte hain:

1. Static
Default value hoti hai. Matlab agar aap kisi element ko position assign nahi karte, to wo static hota hai.
Position normal flow mein hoti hai, yani page ke andar jahan wo element naturally aata hai, wahi rahega.
Ismein aap top, right, bottom, ya left properties ko use nahi kar sakte.

B - Relative
Normal position ke relative hota hai. Ismein element apni normal jagah par hota hai, lekin aap usko top, right, bottom, ya left se move kar sakte ho.
Space uski original position ka rahega, matlab element apni original location se move ho jata hai, but layout mein uski jagah banni rehti hai.


C - Absolute
Closest positioned ancestor ke according hota hai. Matlab agar parent element pe relative, absolute, ya fixed position set hai, to ye uske according position lega. Agar aisa koi ancestor nahi hai, to ye page ke starting point (viewport) se position lega.
Normal flow se remove ho jata hai, yani element apni normal jagah ko affect nahi karta.

D - fixed
Viewport ke according hota hai. Matlab ye element screen pe fixed rahta hai, chahe aap page ko scroll karein.
Normal flow se remove hota hai, aur scroll karte waqt bhi apni jagah par fixed rehta hai.

Note:-


    1- so if i use position relative and give both property top and bottom, then it gives preference to top & for the left and right case, it will give preference to left
    3- we use position:unset to override the position property which is present in another css file  
    4- when we use position:absolute then its height and width becomes zero and will come outside of below element 
    5- We use inset to give styling from top, bottom, left and right  
    6 - for relative, element apne position se top, bottom , left and right krta h
    7 - for absolute, wo top se leta h irrespective of element position
    8 - Position property is easy 

