Début
	Fonction estUnPalindrome(mot)
		Lire mot
		nb_caractere <- nbCar(mot)
		palindrome <- vrai
		Pour chaque lettre à l'indice i de mot
			Si  mot[i] != mot[nb_caractere -i]
				palindrome <- faux
			FinSi
		FinPour
		Si palindrome <- vrai Alors
			Retourner "Ce mot est un palindrome"
		Sinon
			Retourner "Ce mot n'est pas un palindrome"
		FinSi
	FinProcédure
Fin