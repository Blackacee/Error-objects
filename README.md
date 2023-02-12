# Error-objects
 
try {
 throw new Error('Useful message');
} catch (error) {
 console.log('Something went wrong! ' + error.message);
}
