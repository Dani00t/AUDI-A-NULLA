DATI AUDIA4 A4 NULLA
AudiA4  L = 4,709 m; 
        H = 1.457 m; 
        W = 1.983 m;
	Aref = 1.15 m^2;

- snappyHexMesh sempre uguale

- blockMesh:
RISULTATI: Aref = 1.15, 2000 iterazioni (cd mediato su ultime 500)

	- MESH3: (100 20 20) --> Lv0 = 0.45 m
		celle = 4175589
		log.checkMesh OK
		CD = 0.293419
		Cd MEDIO = 0.2936413774

- controlDict: 2000 iterazioni; medio ultime 500

- forceCoeffs:
	rho = 1 perché incomprimibile (ho letto su internet);
	Se voglio calcolare le forze metti rho = 1.225;
	p = 0;
	Aref = 1.15; 
	U = 30;