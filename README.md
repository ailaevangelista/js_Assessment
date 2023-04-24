# Js_Assessment

This program is a simple contract written in a Javascript. The goal of this project is to create an open platform where each user can create their own NFT.

## Description
This project aims to develop an open platform where users can each develop their own NFT.

### Executing Program
To run this program, i use programiz javascript because i cant connet my github on gitpod, an online Javascript IDE. To get started, go to the programiz website at https://www.programiz.com/javascript/online-compiler/.

Once you are on the programiz website,  Copy and paste the following code into the file:


#### CODES

```// create a variable to hold your NFT's
const x = []

// this function will take in some values as parameters, create an
// NFT object using the parameters passed to it for its metadata, 
// and store it in the variable above.
function mint(name, eyeColor, shirt, accessory) {
 const NFT = {
    "name" : name,
    "eyeColor" : eyeColor,
    "shirt" : shirt,
    "accessory" : accessory

 }
 x.push(NFT);
 console.log("Minted: " + name);
}

// create a "loop" that will go through an "array" of NFT's
// and print their metadata with console.log()
function list() {
    for (let i=0; i<x.length; i++){
        console.log("\nID:\t\t\t\t\t\t" + (i+1));
        console.log("Name:\t\t\t\t\t" + x[i].name);
        console.log("Eyecolor:\t\t\t" + x[i].eyeColor);
        console.log("Shirt Type:\t\t" + x[i].shirt);
        console.log("Accessory:\t\t" + x[i].accessory);
    }
}

// print the total number of NFTs we have minted to the console
function total() {
    console.log("\nTotal Number of Minted NFTs: ");
    console.log(x.length + " " + "NFTs");
}   

// call your functions below this line
mint("Cazandra", "Blue", "Turtle Neck", "Watch");
mint("Kin", "Pink", "T-shirt", "Ring");
mint("Shanai", "Orange", "Sleeveless", "Necklace");
mint("CM", "Ube", "Coat", "Earings");
list();
total(); ```


#### Authors
NTCIAN Aila Marie Evangelista Discord @8211051@NTC.EDU.PH

##### License
This project is licensed under the MIT License - see the LICENSE.md file for details. 
