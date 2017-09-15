# Kjellkod

A scripting language that is a play on the name *Kjell*, english-speaking people may be like **wtf**.  
*Kjell* is closely related to the word *Käll*, at least phonetic. *Käll* or *källa* meaning source. 

This is still a work in progress, and this document is mostly to outline the language-structure.

## Structure

### Declaring a variable
```
änna counter = ny integer();

änna - tells the interpreter to create a new variable using the next word as the variable-name, and declares the datatype declared after the equal-sign.  
```
If we were to translate this into example C#, it would translate into:
```
integer counter;
```

## Example
```
klass kjell {
	//Echo out sOutput and return 0.
	func äkko ( änna sOutput ) {
		kjell.konsol.logg( sOutput );
		hare gött 0;
	}
}
````
## License
Please see LICENSE included in this repo.