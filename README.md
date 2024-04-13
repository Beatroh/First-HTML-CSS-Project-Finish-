* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    background-color: #202124;
    color: white;
 /*   padding: 14px; */
    min-height: 100vh;
    display: flex;
    flex-direction: column;
    gap: 14px;
    font-family: sans-serif 'Times New Roman', Times, serif;


}
header {
    display: flex;
    align-items: center; /*this is how you add comments */
    justify-content: space-between; /*this allows you to create space between the inputs that you entered.*/
    cursor: pointer;
    padding: 14px;

}

nav,
section {
    display: flex;
    align-items: center;
    gap: 14px; /* this divides the words gives space*/
}

header section img {
    max-width: 40px;
    border-radius: 50%;
    border: 2px solid;
}

.whiteLink {
    color: white;
}

.greyLink {
    color: #bdc1c6;
}
a {
    text-decoration: unset;
    font-size: 1em;
}

a:hover {
    text-decoration: underline;
}

main {
    flex: 1;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    gap: 25px;
    padding: 0 14px;
}

.headertext {
    font-size: 4.5em;
    font-family: 'Times New Roman', Times, serif
    !important;
}

.searchBar {
    display: flex;
    width: 100%;
    max-width: 700px;
    margin: 0 auto; /* the 0 represents the verticle margin and auto is the horixontal if you remove the 0 your margin would take a lot more space */
    gap: 14px;
    border: 1px solid grey;
    padding: 14px;
    border-radius: 24px;



}
.searchBar:hover {
    border-color: transparent;
    background: #363637;
}
/* ???? why do some things require a period in front of it and some don't */

.buttonIconContainer {
    display: flex;
    align-items: center;
    gap: 14px;
}

.iconButton {
    background: transparent;
    border: none;
    color: lightgray;
    font-size: 1.2em;
    cursor: pointer;

}


input {
    background: transparent;
    outline: none;
    border: unset;
    color: white;
    flex: 1;

}

.searchButtonsContainer {
    display: flex;
    align-items: center;
    gap: 14px;
}

.searchButtonsContainer button {
    padding: 10px 14px;
    border-radius: 8px;
    background: #363637;
    border: solid transparent;
    color: white;
    cursor: pointer;

}

.searchButtonsContainer button:hover {
    border: 1px solid darkgrey;

}

.languageSelection {
    color: white;
    
}

.languageSelection {
    display: flex;
    align-items: center; /* Align items vertically */
}

.languageSelection p {
    margin-right: 0px; /* Adjust the value as needed */
    font-size: .9em;
    font-family: 'Times New Roman';
}

.languageSelection div {
    margin-right: 10px; /* Adjust the value as needed */
    font-family: 'Times New Roman';
}

.languageSelection span {
    color: #8ab4f8;
    cursor: pointer;
    font-size: .9em;
}

.languageSelection span:hover {
    text-decoration: underline;
}
.footer {
    display: flex;
    flex-direction: column;
}

footer > section{
    padding: 16px;
    border: 1px solid  rgb(27, 26, 26);
    background-color: rgb(27, 26, 26);
}

footer > section:last-child {
    display: flex;
    align-items: center;
    justify-content: space-around;
    border: 1px solid rgb(49, 49, 49);
    background-color: rgb(27, 26, 26);

}

.footerLink {
    display: flex;
    align-items: center;
    gap: 8px;
    margin-right: 15px;
}



.footerLink a {
    cursor: pointer;
    margin-right: 23px;
}

@media (min-width: 540px) {
    footer > section:last-child {
        flex-direction: row;
    }
}
