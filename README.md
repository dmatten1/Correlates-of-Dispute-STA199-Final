# project

Project repo for STA 199 - Fall 2024.



<<<<<<< HEAD
#	Variable	Type	Len	Format	Informat	Label
1. 	unitid	Num	8			unitid
2. 	OPEID	Char	10	$10.	$10.	OPE ID
3	institution_name	Char	65	$65.	$65.	institution_name
4	addr1_txt	Char	58	$58.	$58.	addr1_txt
5	addr2_txt	Char	35	$35.	$35.	addr2_txt
6	city_txt	Char	25	$25.	$25.	city_txt
7	state_cd	Char	2	$2.	$2.	state_cd
8	zip_text	Char	9	$9.	$9.	zip_text
9	ClassificationCode	Num	8			ClassificationCode
10	classification_name	Char	34	$34.	$34.	classification_name
11	ClassificationOther	Char	50	$50.	$50.	ClassificationOther
12	EFMaleCount	Num	8			Total Men
13	EFFemaleCount	Num	8			Total Women
14	EFTotalCount	Num	8			Grand Total
15	sector_cd	Num	8			sector_cd
16	sector_name	Char	35	$35.	$35.	sector_name
17	STUDENTAID_MEN	Num	8			Athletic Student Aid/Men's Team
18	STUDENTAID_WOMEN	Num	8			Athletic Student Aid/Women's Team
19	STUDENTAID_COED	Num	8			Athletic Student Aid/Coed Team
20	STUDENTAID_TOTAL	Num	8			Total Student Aid/ Men's/Women's/Coed Team
21	STUAID_MEN_RATIO	Num	8			Ratio Athletic Student Aid/Men's Team
22	STUAID_WOMEN_RATIO	Num	8			Ratio Athletic Student Aid/Women's Team
23	STUAID_COED_RATIO	Num	8			Ratio Athletic Student Aid/Coed Team
24	RECRUITEXP_MEN	Num	8			Recruiting Expenses for Men's Team
25	RECRUITEXP_WOMEN	Num	8			Recruiting Expenses for Women's Team
26	RECRUITEXP_COED	Num	8			Recruiting Expenses for Coed Team
27	RECRUITEXP_TOTAL	Num	8			Total Recruiting Exp./Men and Women's Team
28	HDCOACH_SALARY_MEN	Num	8			Annual salary per HD Coach/Men's
29	HDCOACH_SALARY_WOMEN	Num	8			Annual Salary per HD Coach/Women's
30	HDCOACH_SALARY_COED	Num	8			Annual Salary per HD Coach/Coed
31	NUM_HDCOACH_MEN	Num	8			# HD Coaches Men's Team
32	NUM_HDCOACH_WOMEN	Num	8			# HD Coaches  Women's Team
33	NUM_HDCOACH_COED	Num	8			# HD Coaches Coed Team
34	HDCOACH_SAL_FTE_MEN	Num	8			Ave. salary per FTE HD Coach/ Men's
35	HDCOACH_SAL_FTE_WOMN	Num	8			Ave. salary per FTE HD Coach/ Women's
36	HDCOACH_SAL_FTE_COED	Num	8			Ave. salary per FTE HD Coach/Coed
37	FTE_HDCOACH_MEN	Num	8			# FTE HD Coach/Men's Team
38	FTE_HDCOACH_WOMEN	Num	8			# FTE HD Coach/Women's Team
39	FTE_HDCOACH_COED	Num	8			# FTE HD Coach/Coed Team
40	ASCOACH_SALARY_MEN	Num	8			Annual Salary/Assist. Coach/Men's
41	ASCOACH_SALARY_WOMEN	Num	8			Annual Salary/Assist. Coach/Women's
42	ASCOACH_SALARY_COED	Num	8			Annual Salary/Assist. Coach/Coed
43	NUM_ASCOACH_MEN	Num	8			# Assist. Coach/Men's
44	NUM_ASCOACH_WOMEN	Num	8			# Assist. Coach/Women's
45	NUM_ASCOACH_COED	Num	8			# Assist. Coach/Coed
46	ASCOACH_SAL_FTE_MEN	Num	8			Ave. salary per FTE/Men's
47	ASCOACH_SAL_FTE_WOMN	Num	8			Ave. salary per FTE/Women's
48	ASCOACH_SAL_FTE_COED	Num	8			Ave. salary per FTE/Coed
49	FTE_ASCOACH_MEN	Num	8			# FTEs Assist. Coach/Men's
50	FTE_ASCOACH_WOMEN	Num	8			# FTEs Assist. Coach/Women's
51	FTE_ASCOACH_COED	Num	8			# FTEs Assist. Coach/Coed
52	IL_PARTIC_MEN	Num	8			Total # Participants Men
53	IL_PARTIC_WOMEN	Num	8			Total # Participants Women
54	IL_PARTIC_COED_MEN	Num	8			Total # Participants Men Coed
55	IL_PARTIC_COED_WOMEN	Num	8			Total # Participants Women Coed
56	IL_SUM_PARTIC_MEN	Num	8			Total # Participants Men/Men Coed
57	IL_SUM_PARTIC_WOMEN	Num	8			Total # Participants Women/Women Coed
58	IL_OPEXPPERPART_MEN	Num	8			Total Exp. Per Participant/Men
59	IL_OPEXPPERTEAM_MEN	Num	8			Total Exp. Per Team/Men
60	IL_OPEXPPERPART_WOMEN	Num	8			Total Exp. Per Participant/Women
61	IL_OPEXPPERTEAM_WOMEN	Num	8			Total Exp. Per Team/Women
62	IL_TOTAL_OPEXP_MENWOMEN	Num	8			Total Exp. Men and Women
63	IL_OPEXPPERPART_COED_MEN	Num	8			Total Exp. Per Participant/Coed Men
64	IL_OPEXPPERTEAM_COED_MEN	Num	8			Total Exp. Per Team/Coed Men
65	IL_OPEXP_PART_COED_WOMEN	Num	8			Total Exp. Per Participant Women/Coed
66	IL_OPEXP_TEAM_COED_WOMEN	Num	8			Total Exp. Per Team Women/Coed
67	IL_TOTAL_OPEXP_COEDTEAM	Num	8			Total Exp. Coed Men/Coed Women
68	IL_SUM_OPEXPPERPART_MEN	Num	8			Total Exp. Per Participant/Men/Coed Men
69	IL_SUM_OPEXPPERTEAM_MEN	Num	8			Total Exp. Per Team/Men/Coed Men
70	IL_SUM_OPEXPPERPART_WOMEN	Num	8			Total Exp. Per Participant/Women/Coed Women
71	IL_SUM_OPEXPPERTEAM_WOMEN	Num	8			Total Exp. Per Team/Women/Coed Women
72	IL_TOTAL_OPEXP_INCLCOED	Num	8			Total Exp. Men/Women/Coed Men/Women
73	IL_MEN_FTHEADCOACH_MALE	Num	8			Total # Men's HD Coach/Male/Full-Time
74	IL_MEN_PTHEADCOACH_MALE	Num	8			Total # Men's HD Coach/Male/Part-Time
75	IL_MEN_FTUNIVEMPLOY_MALE	Num	8			Total # Men's HD Coach/Male/FTEmp
76	IL_MEN_PTUNIVEMPLOY_MALE	Num	8			Total # Men's HD Coach/Male/PTEmp
77	IL_MEN_FTHEADCOACH_FEM	Num	8			Total # Men's HD Coach/Female/Full-Time
78	IL_MEN_PTHEADCOACH_FEM	Num	8			Total # Men's HD Coach/Female/Part-Time
79	IL_MEN_FTUNIVEMPLOY_FEM	Num	8			Total # Men's HD Coach/Female/FTEmp
80	IL_MEN_PTUNIVEMPLOY_FEM	Num	8			Total # Men's HD Coach/Female/PTEmp
81	IL_MEN_TOTAL_HEADCOACH	Num	8			Total # HD Coach/Men's Team
82	IL_WOMEN_FTHDCOACH_MALE	Num	8			Total # Women's HD Coach/Male/Full-Time
83	IL_WOMEN_PTHDCOACH_MALE	Num	8			Total # Women's HD Coach/Male/Part-Time
84	IL_WOMEN_FTUNIVEMP_MALE	Num	8			Total # Women's HD Coach/Male/FTEmp
85	IL_WOMEN_PTUNIVEMP_MALE	Num	8			Total # Women's HD Coach/Male/PTEmp
86	IL_WOMEN_FTHDCOACH_FEM	Num	8			Total # Women's HD Coach/Female/Full-Time
87	IL_WOMEN_PTHDCOACH_FEM	Num	8			Total # Women's HDCoach/Female/Part-Time
88	IL_WOMEN_FTUNIVEMP_FEM	Num	8			Total # Women's HDCoach/Female/FTEmp
89	IL_WOMEN_PTUNIVEMP_FEM	Num	8			Total # Women's HD Coach/Female/PTEmp
90	IL_WOMEN_TOTAL_HDCOACH	Num	8			Total # HDCoach/Women's Team
91	IL_COED_FTHDCOACH_MALE	Num	8			Total # Coed HD Coach//Male/Full-Time
92	IL_COED_PTHDCOACH_MALE	Num	8			Total # Coed HD Coach/Male/Part-Time
93	IL_COED_FTUNIVEMP_MALE	Num	8			Total # Coed HD Coach/Male/FTEmp
94	IL_COED_PTUNIVEMP_MALE	Num	8			Total # Coed HD Coach/Male/PTEmp
95	IL_COED_FTHDCOACH_FEM	Num	8			Total # Coed HD Coach/Female/Full-Time
96	IL_COED_PTHDCOACH_FEM	Num	8			Total # Coed HD Coach/Female/Part-Time
97	IL_COED_FTUNIVEMP_FEM	Num	8			Total # Coed HD Coach/Female/FTEmp
98	IL_COED_PTUNIVEMP_FEM	Num	8			Total # Coed HD Coach/Female/PTEmp
99	IL_COED_TOTAL_HDCOACH	Num	8			Total # Coed Team HD Coaches
100	IL_SUM_FTHDCOACH_MALE	Num	8			Total # Male HD Coaches/Men/Women/Coed/Full-Time
101	IL_SUM_PTHDCOACH_MALE	Num	8			Total # Male HD Coaches/Men/Women/Coed/Part-Time
102	IL_SUM_FTUNIVEMP_MALE	Num	8			Total # Male HD Coaches/Men/Women/Coed/FTEmp
103	IL_SUM_PTUNIVEMP_MALE	Num	8			Total # Male HD Coaches/Men/Women/Coed/PTEmp
104	IL_SUM_FTHDCOACH_FEM	Num	8			Total # Female HD Coaches/Men/Women/Coed/Full-Time
105	IL_SUM_PTHDCOACH_FEM	Num	8			Total # Female HD Coaches/Men/Women/Coed/Part-Time
106	IL_SUM_FTUNIVEMP_FEM	Num	8			Total # Female HD Coaches/Men/Women/Coed/FTEmp
107	IL_SUM_PTUNIVEMP_FEM	Num	8			Total # Female HD Coaches/Men/Women/Coed/PTEmp
108	IL_SUM_TOTAL_HDCOACH	Num	8			Total # HD Coaches/Men/Women/Coed Teams
109	IL_MEN_FTASCOACH_MALE	Num	8			Total # Men's Assist. Coach/Male/Full-Time
110	IL_MEN_PTASCOACH_MALE	Num	8			Total # Men's Assist. Coach/Male/Part-Time
111	IL_MEN_FTACUNIVEMP_MALE	Num	8			Total # Men's Assist. Coach/Male/FTEmp
112	IL_MEN_PTACUNIVEMP_MALE	Num	8			Total # Men's Assist. Coach/Male/PTEmp
113	IL_MEN_FTASSTCOACH_FEM	Num	8			Total # Men's Assist. Coach/Female/Full-Time
114	IL_MEN_PTASSTCOACH_FEM	Num	8			Total # Men's Assist. Coach/Female/Part-Time
115	IL_MEN_FTACUNIVEMP_FEM	Num	8			Total # Men's Assist. Coach/Female/FTEmp
116	IL_MEN_PTACUNIVEMP_FEM	Num	8			Total # Men's Assist. Coach/Female/PTEmp
117	IL_MEN_TOTAL_ASSTCOACH	Num	8			Total Number of Total Assist. Coaches in Men's Team
118	IL_WOMEN_FTASCOACH_MALE	Num	8			Total # Women's Assist. Coach/Male/Full-Time
119	IL_WOMEN_PTASCOACH_MALE	Num	8			Total # Women's Assist. Coach/Male/Part-Time
120	IL_WOMEN_FTACUNEMP_MALE	Num	8			Total # Women's Assist. Coach/Male/FTEmp
121	IL_WOMEN_PTACUNEMP_MALE	Num	8			Total # Women's Assist. Coach/Male/PTEmp
122	IL_WOMEN_FTASTCOACH_FEM	Num	8			Total # Women's Assist. Coach/Female/Full-Time
123	IL_WOMEN_PTASTCOACH_FEM	Num	8			Total # Women's Assist. Coach/Female/Part-Time
124	IL_WOMN_FTACUNIVEMP_FEM	Num	8			Total # Women's Assist. Coach/Female/FTEmp
125	IL_WOMN_PTACUNIVEMP_FEM	Num	8			Total # Women's Assist. Coach Female/PTEmp
126	IL_WOMEN_TOTAL_ASTCOACH	Num	8			Total Number of Total Assist. Coaches in Women's Team
127	IL_COED_FTASCOACH_MALE	Num	8			Total # Coed Assist. Coach/Male/Full-Time
128	IL_COED_PTASCOACH_MALE	Num	8			Total # Coed Assist. Coach/Male/Part-Time
129	IL_COED_FTACUNEMP_MALE	Num	8			Total # Coed Assist. Coach/Male/FTEmp
130	IL_COED_PTACUNEMP_MALE	Num	8			Total # Coed Assist. Coach/Male/PTEmp
131	IL_COED_FTASTCOACH_FEM	Num	8			Total # Coed Assist. Coach/Female/Full-Time
132	IL_COED_PTASTCOACH_FEM	Num	8			Total # Coed Assist. Coach/Female/Part-Time
133	IL_COED_FTACUNIVEMP_FEM	Num	8			Total # Coed Assist. Coach/Female/FTEmp
134	IL_COED_PTACUNIVEMP_FEM	Num	8			Total # Coed Assist. Coach/Female/PTEmp
135	IL_COED_TOTAL_ASTCOACH	Num	8			Total # of Total Assist. Coaches in Coed Team
136	IL_SUM_FTASCOACH_MALE	Num	8			Total # Assist. Coach/Men/Women/Coed/Male/Full-Time
137	IL_SUM_PTASCOACH_MALE	Num	8			Total # Assist. Coach/Men/Women/Coed/Male/Part-Time
138	IL_SUM_FTACUNIVEMP_MALE	Num	8			Total # Assist. Coach/Men/Women/Coed/Male/FTEmp
139	IL_SUM_PTACUNIVEMP_MALE	Num	8			Total # Assist. Coach/Men/Women/Coed/Male/PTEmp
140	IL_SUM_FTASCOACH_FEM	Num	8			Total # Assist. Coach/Men/Women/Coed/Female/Full-Time
141	IL_SUM_PTASCOACH_FEM	Num	8			Total # Assist. Coach/Men/Women/Coed/Female/Part-Time
142	IL_SUM_FTACUNIVEMP_FEM	Num	8			Total # Assist. Coach/Men/Women/Coed/Female/FTEmp
143	IL_SUM_PTACUNIVEMP_FEM	Num	8			Total # Assist. Coach/Men/Women/Coed/Female/PTEmp
144	IL_SUM_TOTAL_ASSTCOACH	Num	8			Total # Assist. Coaches/Men/Women/Coed Teams
145	IL_REV_MEN	Num	8			Total Revenues per Team for Men
146	IL_REV_WOMEN	Num	8			Total Revenues per Team for Women
147	IL_TOTAL_REV_MENWOMEN	Num	8			Total Revenues per Team for Men and Women
148	IL_REV_COED_MEN	Num	8			Total Revenues per Team for Coed Men
149	IL_REV_COED_WOMEN	Num	8			Total Revenues per Team for Coed Women
150	IL_TOTAL_REV_COED	Num	8			Total Revenues per Team/ Coed Men/Coed Women
151	IL_REVENUE_MENALL	Num	8			Total Revenues per Team for Men's and Coed Men
152	IL_REVENUE_WOMENALL	Num	8			Total Revenues per Team for Women's and Coed Women
153	IL_TOTAL_REVENUE_ALL	Num	8			Total Revenues per Team and Total Coed Revenues
154	IL_EXP_MEN	Num	8			Total Expenses per Team for Men
155	IL_EXP_WOMEN	Num	8			Total Expenses per Team for Women
156	IL_TOTAL_EXP_MENWOMEN	Num	8			Total Expenses per Team for Men and Women
157	IL_EXP_COED_MEN	Num	8			Total Expenses per Team for Coed Men
158	IL_EXP_COED_WOMEN	Num	8			Total Expenses per Team for Coed Women
159	IL_TOTAL_EXP_COED	Num	8			Total Expenses per Team/Coed Men and Coed Women
160	IL_EXPENSE_MENALL	Num	8			Total Expenses per Team for Men's and Coed Men
161	IL_EXPENSE_WOMENALL	Num	8			Total Expenses per Team for Women's and Coed Women
162	IL_TOTAL_EXPENSE_ALL	Num	8			Total Sum of Expenses per Team and Total Coed Expenses
163	UNDUP_CT_PARTIC_MEN	Num	8			Unduplicated Counts of Participants in Men's Team and Men's Coed Team
164	UNDUP_CT_PARTIC_WOMEN	Num	8			Unduplicated Counts of Participants in Women's Team and Women's Coed Team.
165	TOT_REVENUE_ALL_NOTALLOC	Num	8			Total Revenues Not Allocated by Gender/Sport
166	TOT_EXPENSE_ALL_NOTALLOC	Num	8			Total Expenses Not Allocated by Gender/Sport
167	GRND_TOTAL_REVENUE	Num	8			Grand Total Revenues
168	GRND_TOTAL_EXPENSE	Num	8			Grand Total Expenses
169	PARTIC_MEN_Baseball	Num	8			# Participants Men. Sport: Baseball
170	PARTIC_MEN_Bskball	Num	8			# Participants Men. Sport: Basketball
171	PARTIC_MEN_Trckcomb	Num	8			# Participants Men. Sport:  All Track Combined
172	PARTIC_MEN_Diving	Num	8			# Participants Men. Sport: Diving
173	PARTIC_MEN_Fencing	Num	8			# Participants Men. Sport: Fencing
174	PARTIC_MEN_FldHcky	Num	8			# Participants Men. Sport: Field Hockey
175	PARTIC_MEN_Football	Num	8			# Participants Men. Sport: Football
176	PARTIC_MEN_Golf	Num	8			# Participants Men. Sport: Golf
177	PARTIC_MEN_Gymn	Num	8			# Participants Men. Sport: Gymnastics
178	PARTIC_MEN_IceHcky	Num	8			# Participants Men. Sport: Ice Hockey
179	PARTIC_MEN_Lacrsse	Num	8			# Participants Men. Sport: Lacrosse
180	PARTIC_MEN_Rifle	Num	8			# Participants Men. Sport: Rifle
181	PARTIC_MEN_Rowing	Num	8			# Participants Men. Sport: Rowing
182	PARTIC_MEN_Skiing	Num	8			# Participants Men. Sport: Skiing
183	PARTIC_MEN_Soccer	Num	8			# Participants Men. Sport: Soccer
184	PARTIC_MEN_Softball	Num	8			# Participants Men. Sport: Softball
185	PARTIC_MEN_Squash	Num	8			# Participants Men. Sport: Squash
186	PARTIC_MEN_SwimDivng	Num	8			# Participants Men. Sport: Swimming and Diving
187	PARTIC_MEN_Swimming	Num	8			# Participants Men. Sport: Swimming
188	PARTIC_MEN_SynSwim	Num	8			# Participants Men. Sport: Synchronized Swimming
189	PARTIC_MEN_Tennis	Num	8			# Participants Men. Sport: Tennis
190	PARTIC_MEN_TrkFldIn	Num	8			# Participants Men. Sport: Track and Field, Indoor
191	PARTIC_MEN_TrkFldOut	Num	8			# Participants Men. Sport: Track and Field, Outdoor
192	PARTIC_MEN_XCountry	Num	8			# Participants Men. Sport: Track and Field, X-Country
193	PARTIC_MEN_Vollball	Num	8			# Participants Men. Sport: Volleyball
194	PARTIC_MEN_WaterPolo	Num	8			# Participants Men. Sport: Water Polo
195	PARTIC_MEN_Wrestling	Num	8			# Participants Men. Sport: Wrestling
196	PARTIC_MEN_OthSpts	Num	8			# Participants Men. Sport: Other Sports
197	PARTIC_MEN_Archery	Num	8			# Participants Men. Sport: Archery
198	PARTIC_MEN_Badminton	Num	8			# Participants Men. Sport: Badminton
199	PARTIC_MEN_BchVoll	Num	8			# Participants Men. Sport: Beach Volleyball
200	PARTIC_MEN_Bowling	Num	8			# Participants Men. Sport: Bowling
201	PARTIC_MEN_Eqstrian	Num	8			# Participants Men. Sport: Equestrian
202	PARTIC_MEN_Rodeo	Num	8			# Participants Men. Sport: Rodeo
203	PARTIC_MEN_Sailing	Num	8			# Participants Men. Sport: Sailing
204	PARTIC_MEN_TblTennis	Num	8			# Participants Men. Sport: Table Tennis
205	PARTIC_MEN_WgtLift	Num	8			# Participants Men. Sport: Weight Lifting
206	PARTIC_WOMEN_Baseball	Num	8			# Participants Women. Sport: Baseball
207	PARTIC_WOMEN_Bskball	Num	8			# Participants Women. Sport: Basketball
208	PARTIC_WOMEN_Trckcomb	Num	8			# Participants Women. Sport:  All Track Combined
209	PARTIC_WOMEN_Diving	Num	8			# Participants Women. Sport: Diving
210	PARTIC_WOMEN_Fencing	Num	8			# Participants Women. Sport: Fencing
211	PARTIC_WOMEN_FldHcky	Num	8			# Participants Women. Sport: Field Hockey
212	PARTIC_WOMEN_Football	Num	8			# Participants Women. Sport: Football
213	PARTIC_WOMEN_Golf	Num	8			# Participants Women. Sport: Golf
214	PARTIC_WOMEN_Gymn	Num	8			# Participants Women. Sport: Gymnastics
215	PARTIC_WOMEN_IceHcky	Num	8			# Participants Women. Sport: Ice Hockey
216	PARTIC_WOMEN_Lacrsse	Num	8			# Participants Women. Sport: Lacrosse
217	PARTIC_WOMEN_Rifle	Num	8			# Participants Women. Sport: Rifle
218	PARTIC_WOMEN_Rowing	Num	8			# Participants Women. Sport: Rowing
219	PARTIC_WOMEN_Skiing	Num	8			# Participants Women. Sport: Skiing
220	PARTIC_WOMEN_Soccer	Num	8			# Participants Women. Sport: Soccer
221	PARTIC_WOMEN_Softball	Num	8			# Participants Women. Sport: Softball
222	PARTIC_WOMEN_Squash	Num	8			# Participants Women. Sport: Squash
223	PARTIC_WOMEN_SwimDivng	Num	8			# Participants Women. Sport: Swimming and Diving
224	PARTIC_WOMEN_Swimming	Num	8			# Participants Women. Sport: Swimming
225	PARTIC_WOMEN_SynSwim	Num	8			# Participants Women. Sport: Synchronized Swimming
226	PARTIC_WOMEN_Tennis	Num	8			# Participants Women. Sport: Tennis
227	PARTIC_WOMEN_TrkFldIn	Num	8			# Participants Women. Sport: Track and Field, Indoor
228	PARTIC_WOMEN_TrkFldOut	Num	8			# Participants Women. Sport: Track and Field, Outdoor
229	PARTIC_WOMEN_XCountry	Num	8			# Participants Women. Sport: Track and Field, X-Country
230	PARTIC_WOMEN_Vollball	Num	8			# Participants Women. Sport: Volleyball
231	PARTIC_WOMEN_WaterPolo	Num	8			# Participants Women. Sport: Water Polo
232	PARTIC_WOMEN_Wrestling	Num	8			# Participants Women. Sport: Wrestling
233	PARTIC_WOMEN_OthSpts	Num	8			# Participants Women. Sport: Other Sports
234	PARTIC_WOMEN_Archery	Num	8			# Participants Women. Sport: Archery
235	PARTIC_WOMEN_Badminton	Num	8			# Participants Women. Sport: Badminton
236	PARTIC_WOMEN_BchVoll	Num	8			# Participants Women. Sport: Beach Volleyball
237	PARTIC_WOMEN_Bowling	Num	8			# Participants Women. Sport: Bowling
238	PARTIC_WOMEN_Eqstrian	Num	8			# Participants Women. Sport: Equestrian
239	PARTIC_WOMEN_Rodeo	Num	8			# Participants Women. Sport: Rodeo
240	PARTIC_WOMEN_Sailing	Num	8			# Participants Women. Sport: Sailing
241	PARTIC_WOMEN_TblTennis	Num	8			# Participants Women. Sport: Table Tennis
242	PARTIC_WOMEN_WgtLift	Num	8			# Participants Women. Sport: Weight Lifting
243	PARTIC_COED_MEN_Baseball	Num	8			# Participants Men Coed. Sport: Baseball
244	PARTIC_COED_MEN_Bskball	Num	8			# Participants Men Coed. Sport: Basketball
245	PARTIC_COED_MEN_Trckcomb	Num	8			# Participants Men Coed. Sport:  All Track Combined
246	PARTIC_COED_MEN_Diving	Num	8			# Participants Men Coed. Sport: Diving
247	PARTIC_COED_MEN_Fencing	Num	8			# Participants Men Coed. Sport: Fencing
248	PARTIC_COED_MEN_FldHcky	Num	8			# Participants Men Coed. Sport: Field Hockey
249	PARTIC_COED_MEN_Football	Num	8			# Participants Men Coed. Sport: Football
250	PARTIC_COED_MEN_Golf	Num	8			# Participants Men Coed. Sport: Golf
251	PARTIC_COED_MEN_Gymn	Num	8			# Participants Men Coed. Sport: Gymnastics
252	PARTIC_COED_MEN_IceHcky	Num	8			# Participants Men Coed. Sport: Ice Hockey
253	PARTIC_COED_MEN_Lacrsse	Num	8			# Participants Men Coed. Sport: Lacrosse
254	PARTIC_COED_MEN_Rifle	Num	8			# Participants Men Coed. Sport: Rifle
255	PARTIC_COED_MEN_Rowing	Num	8			# Participants Men Coed. Sport: Rowing
256	PARTIC_COED_MEN_Skiing	Num	8			# Participants Men Coed. Sport: Skiing
257	PARTIC_COED_MEN_Soccer	Num	8			# Participants Men Coed. Sport: Soccer
258	PARTIC_COED_MEN_Softball	Num	8			# Participants Men Coed. Sport: Softball
259	PARTIC_COED_MEN_Squash	Num	8			# Participants Men Coed. Sport: Squash
260	PARTIC_COED_MEN_SwimDivng	Num	8			# Participants Men Coed. Sport: Swimming and Diving
261	PARTIC_COED_MEN_Swimming	Num	8			# Participants Men Coed. Sport: Swimming
262	PARTIC_COED_MEN_SynSwim	Num	8			# Participants Men Coed. Sport: Synchronized Swimming
263	PARTIC_COED_MEN_Tennis	Num	8			# Participants Men Coed. Sport: Tennis
264	PARTIC_COED_MEN_TrkFldIn	Num	8			# Participants Men Coed. Sport: Track and Field, Indoor
265	PARTIC_COED_MEN_TrkFldOut	Num	8			# Participants Men Coed. Sport: Track and Field, Outdoor
266	PARTIC_COED_MEN_XCountry	Num	8			# Participants Men Coed. Sport: Track and Field, X-Country
267	PARTIC_COED_MEN_Vollball	Num	8			# Participants Men Coed. Sport: Volleyball
268	PARTIC_COED_MEN_WaterPolo	Num	8			# Participants Men Coed. Sport: Water Polo
269	PARTIC_COED_MEN_Wrestling	Num	8			# Participants Men Coed. Sport: Wrestling
270	PARTIC_COED_MEN_OthSpts	Num	8			# Participants Men Coed. Sport: Other Sports
271	PARTIC_COED_MEN_Archery	Num	8			# Participants Men Coed. Sport: Archery
272	PARTIC_COED_MEN_Badminton	Num	8			# Participants Men Coed. Sport: Badminton
273	PARTIC_COED_MEN_BchVoll	Num	8			# Participants Men Coed. Sport: Beach Volleyball
274	PARTIC_COED_MEN_Bowling	Num	8			# Participants Men Coed. Sport: Bowling
275	PARTIC_COED_MEN_Eqstrian	Num	8			# Participants Men Coed. Sport: Equestrian
276	PARTIC_COED_MEN_Rodeo	Num	8			# Participants Men Coed. Sport: Rodeo
277	PARTIC_COED_MEN_Sailing	Num	8			# Participants Men Coed. Sport: Sailing
278	PARTIC_COED_MEN_TblTennis	Num	8			# Participants Men Coed. Sport: Table Tennis
279	PARTIC_COED_MEN_WgtLift	Num	8			# Participants Men Coed. Sport: Weight Lifting
=======
EADA Variables in Creation Order
>>>>>>> ad1a63e035a8e99570c2354361f0f43288c95a9d


#	Variable	
Survey Year	
UNITID	
OPE ID	
Institution Name	
State 
CD	
Classification Name	
Sanction Code	
Sanction Name	
Male Undergraduates	
Female Undergraduates	
Total Undergraduates	
\# Participants Men's Team	Total
Operating Expenses per Participant/Men's Team
Operating Expenses per Team/Men's Team	
Revenues Men's Team	Total