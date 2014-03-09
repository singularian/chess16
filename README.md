Chess16
=======

Chess 16 is a (16 by 16 square) variant of chess.
The idea is to increase the difficulty of chess for computers.
The pawns can move from 1 to 6 squares ahead on the first move.
The objective is to create a much more challenging variation
for computers which is a superset of conventional chess and contains a larger opening library.
There are 256 (16 by 16) squares compared to 64 in a normal chess game. There is a larger space to
play the game in. In total there are 192 (16 by 12) open square board spaces verses 32 (8 by 4) in a conventional
chess game.

This doesn't try to add new pieces so that it is a more conventional variant of chess. It has 1 King to maintain conventions.

There are 32 pieces per side. These pieces are: 

	4 Rooks   (R)
	4 Bishops (B)
	4 Knights (N)
	3 Queens  (Q)
	1 King    (K)
	16 Pawns  (P)

This is an alternative piece list with 1 less queen (1 is replaced by a bishop) and 5 bishops. 

	4 Rooks   (R)
	5 Bishops (B)
	4 Knights (N)
	2 Queens  (Q)
	1 King    (K)
	16 Pawns  (P)



 
Castling is also different. These will be updated later.

# Variation 16 by 8

A 16 by 8 board has this configuration. It features 64 spaces with a more compact structure.
https://github.com/singularian/chess16/blob/master/images/chess168_Board2.png


		1	2	3	4	5	6	7	8	9	10	11	12	13	14	15	16
		a	b	c	d	e	f	g	h	I	j	k	l	m	N	o	P
	8	R	R	N	N	B	B	Q	Q	K	Q	B	B	N	N	R	R
	7	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P																																
	6	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.																
	5	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.															
	4	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.															
	3	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.															
	2	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P
	1	R	R	N	N	B	B	Q	Q	K	Q	B	B	N	N	R	R

# Variation 16 by 16

A 16 by 16 board has this configuration
https://github.com/singularian/chess16/blob/master/images/chess16_Board2.png


		1	2	3	4	5	6	7	8	9	10	11	12	13	14	15	16
		a	b	c	d	e	f	g	h	I	j	k	l	m	N	o	P
	16	R	R	N	N	B	B	Q	Q	K	Q	B	B	N	N	R	R
	15	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P
	14	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.															
	13	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.															
	12	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.															
	11	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.															
	10	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.															
	9	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.															
	8	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.															
	7	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.															
	6	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.															
	5	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.															
	4	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.															
	3	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.															
	2	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P
	1	R	R	N	N	B	B	Q	Q	K	Q	B	B	N	N	R	R



# Variation 32 by 16

A 32 by 16 board has this configuration.
Pawns can move from 1 to 14 spaces initially.


https://github.com/singularian/chess16/blob/master/images/chess16_Board2.png


		1	2	3	4	5	6	7	8	9	10	11	12	13	14	15	16
		a	b	c	d	e	f	g	h	I	j	k	l	m	N	o	P
	32	R	R	N	N	B	B	Q	Q	K	Q	B	B	N	N	R	R
	31	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P
	30	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.
	29	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.
	28	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.
	27	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.
	26	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.
	25	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.
	24	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.
	23	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.
	22	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.
	21	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.
	20	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.
	19	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.
	18	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.
	17	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.
	16	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.
	15	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.
	14	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.																
	13	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.																
	12	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.																
	11	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.																
	10	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.																
	9	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.																
	8	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.																
	7	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.																
	6	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.																
	5	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.																
	4	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.																
	3	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.																
	2	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P
	1	R	R	N	N	B	B	Q	Q	K	Q	B	B	N	N	R	R


# Variation 32 by 32


A 32 by 32 board has this configuration.
Pawns can move from 1 to 13 spaces initially.

There are 32 pieces per side. These pieces are: 

	8 Rooks   (R)
	8 Bishops (B)
	10 Knights (N)
	5 Queens  (Q)
	1 King    (K)
	64 Pawns  (P)

This is an alternative piece list with 1 less queen (1 is replaced by a bishop) and 5 bishops. 

	8 Rooks   (R)
	9 Bishops (B)
	10 Knights (N)
	4 Queens  (Q)
	1 King    (K)
	64 Pawns  (P)

		1 	2	3	4	5	6	7	8	9	10	11	12	13	14	15	16	17	18	19	20	21	22	23	24	25	26	27	28	29	30	31	32
		a 	b	c	d	e	f	g	h	I	j	k	l	m	N	o	p	q	r	s	t	u	v	w	x	y	z	aa	ab	ac	ad	ae	af	
	32	R	R	R	R	N	N	N	N	N	B	B	B	B	Q	Q	Q	K	Q	Q	B	B	B	B	N	N	N	N	N	R	R	R	R
	31	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P
	30	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P
	29	. 	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.
	28	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.
	27	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.
	26	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.
	25	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.
	24	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.
	23	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.
	22	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.
	21	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.
	20	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.
	19	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.
	18	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.
	17	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.
	16	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.
	15	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.
	14	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.		
	13	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.											
	12	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.
	11	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.															
	10	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.															
	9	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.															
	8	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.															
	7	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.															
	6	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.															
	5	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.															
	4	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.															
	3	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P																
	2	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P
	1	R	R	R	R	N	N	N	N	N	B	B	B	B	Q	Q	Q	K	Q	Q	B	B	B	B	N	N	N	N	N	R	R	R	R



# Variation 32 by 32

This is an alternative piece 32 by 32 square chess board with 192 pieces per side in 6 chess rows. 
There are 384 pieces in total.
Pawns can advance from 1 to 8 moves on the first move. 
There are 1024 squares on the board or 16 times as many as a conventional game.
Castling would be more complex.

27 Rooks   (R)
64 Bishops (B)
32 Knights (N)
4 Queens  (Q)
1 King    (K)
64 Pawns  (P)

192       (Total number of player pieces)

This is the board:


		1 	2	3	4	5	6	7	8	9	10	11	12	13	14	15	16	17	18	19	20	21	22	23	24	25	26	27	28	29	30	31	32
		a 	b	c	d	e	f	g	h	I	j	k	l	m	N	o	p	q	r	s	t	u	v	w	x	y	z	aa	ab	ac	ad	ae	af	
	32	R	R	R	R	R	R	R	R	R	R	R	R	R	Q	Q	K	Q	Q	R	R	R	R	R	R	R	R	R	R	R	R	R	R
	31	B	B	B	B	B	B	B	B	B	B	B	B	B	B	B	B	B	B	B	B	B	B	B	B	B	B	B	B	B	B	B	B	
	30	B	B	B	B	B	B	B	B	B	B	B	B	B	B	B	B	B	B	B	B	B	B	B	B	B	B	B	B	B	B	B	B
	29	N	N	N	N	N	N	N	N	N	N	N	N	N	N	N	N	N	N	N	N	N	N	N	N	N	N	N	N	N	N	N	N
	28	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P
	27	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P
	26	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.
	25	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.
	24	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.
	23	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.
	22	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.
	21	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.
	20	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.
	19	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.
	18	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.
	17	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.
	16	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.
	15	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.
	14	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.	
	13	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.
	12	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.
	11	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.															
	10	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.	
	9	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.
	8	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.
	7	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.
	6	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P
	5	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	
	4	N	N	N	N	N	N	N	N	N	N	N	N	N	N	N	N	N	N	N	N	N	N	N	N	N	N	N	N	N	N	N	N
	3	B	B	B	B	B	B	B	B	B	B	B	B	B	B	B	B	B	B	B	B	B	B	B	B	B	B	B	B	B	B	B	B
	2	B	B	B	B	B	B	B	B	B	B	B	B	B	B	B	B	B	B	B	B	B	B	B	B	B	B	B	B	B	B	B	B
	1	R	R	R	R	R	R	R	R	R	R	R	R	R	Q	Q	K	Q	Q	R	R	R	R	R	R	R	R	R	R	R	R	R	R