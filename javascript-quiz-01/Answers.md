Question 1:
Tigger

!!!Question 2:
Write a function secondIndexOf, taking two strings and determining the second occurrence of the second string in the first string. If the search string does not occur twice, -1 should be returned.

Example: secondIndexOf('White Rabbit', 'it') should return 10.

function secondIndexOf(s1, s2) {
 // Use indexOf twice.
}

Question 3:
function equals(a, b) {
    if (a === b) { 
        return "EQUAL";
    } else {
        return "UNEQUAL"
    }
}

Question 4:
if (age > 18) {
    console.log("Old enough");
} else {
    console.log("Too young");
}

Question 5:
function repdigit(n) {
    let x = n.toString();
    let y = false;
    if (n < 0) {
        return false;
    } else if (0 <= n && n < 10) {
        y = true;
    } else {
        for(let i = 0; i < x.length; i++) {
            if (x[i] === x[i + 1]) {
                y = true;
            }
        }
    }
    return y;
}

Question 6:
function unequal(a, b, c) {
    if (a !== b && a !== c && b !== c) { 
        return true;
    } else if (a === b || a === c || b === c) {
        return false;
    }
}

!!!Question 7:
Which of these alerts are going to execute?

What will the results of the expressions be inside if(...)?

if (-1 || 0) alert( 'first' );
if (-1 && 0) alert( 'second' );
if (null || -1 && 1) alert( 'third' );


!!!Question 8:
Write the code which asks for a login with prompt.

If the visitor enters "Admin", then prompt for a password, if the input is an empty line – show “Canceled”, if it’s another string – then show “I don’t know you”.

The password is checked as follows:

If it equals “TheMaster”, then show “Welcome!”, Another string – show “Wrong password”, For an empty string or cancelled input, show “Canceled”

Refer to the schema below:
