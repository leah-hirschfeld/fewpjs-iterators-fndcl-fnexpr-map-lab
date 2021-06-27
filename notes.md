

3. Capitalize each word 
tutorials[0].charAt(0).toUpperCase()

tutorials[0].split(' ')[0].charAt(0).toUpperCase()

4. Put each word back together
5. Put each sentence back into the array

const splitTutorials = tutorials.split(' ')

function splitTutorials(array, i) {
    return array.split(i, i-1);
}