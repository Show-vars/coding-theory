NAME
		java-gf16 - simple calculator for Galois field type GF(2^4) and basic API.
		java-gf16-gui - gui frontend for java-gf16.
DESCRIPTION
		java-gf16 is a simple console calculator in the Galois field and Reed-Solomon encoder and a library with a basic API written in java.
		
		Commands for java-gf16 and java-gf16-gui:
		
		Commands: 
		+a b c ...
			calculate summ of elements where a,b,c... is a terms and print result. Input elements can be both positive and negative.
			
		*a b c ...
			calculate multiple of elements, where a,b,c... is a multipliers and print result. Input elements can be both positive and negative.
			
		$a b,c,d...
			substitute 'a' to polynomial b,c,d..., calculate it and print result.
			
		/0011010101001...
			test coding. Lenght of input sequence must be less than 44, otherwise sequence will be cuted.
			
		da,b,c...
			apply DFT (Discrete Fourie Transform) to polynomial a,b,c..., and print result.
			
		q
			exit
