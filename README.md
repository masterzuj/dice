# dice

![dice](https://github.com/user-attachments/assets/1506a42f-da49-4de7-a6f7-ee4f2f68bac3)


    git clone https://github.com/masterzuj/dice.git



You can change the picture on dice in the href:

        <image x="100" y="180" width="20" height="20" href="./earth.png" /><!--7 -->
        <image x="45" y="155" width="20" height="20" href="./chip.png" /><!--6 -->
        <image x="20" y="100" width="20" height="20" href="./arrow.png" /><!--5 -->
        <image x="45" y="45" width="20" height="20" href="./cross.png" /><!--4 -->
        <image x="100" y="20" width="20" height="20" href="./earth.png" /><!--3 -->
        <image x="155" y="45" width="20" height="20" href="./chip.png" /><!--2 -->
        <image x="180" y="100" width="20" height="20" href="./arrow.png" /><!--1 -->
        <image x="155" y="155" width="20" height="20" href="./cross.png" /><!--8 -->


Also you can change the link, wich opens 
when the dice was rolled

    var numberwin = [
            { number: 1, image: "./arrow.png", href: "./arrow.png" },
            { number: 2, image: "./chip.png", href: "./chip.png" },
            { number: 3, image: "./earth.png", href: "./earth.png" },
            { number: 4, image: "./cross.png", href: "./cross.png" },
            { number: 5, image: "./arrow.png", href: "./arrow.png" },
            { number: 6, image: "./chip.png", href: "./chip.png" },
            { number: 7, image: "./earth.png", href: "./earth.png" },
            { number: 8, image: "./cross.png", href: "./cross.png" },
            { number: 0, image: "", href: "https://zujkov.com/" },
        ];
