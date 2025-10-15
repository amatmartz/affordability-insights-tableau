# Tableau Calcs (stub)
Params: pBaselineYear, pRate, pTermYears, pDownPaymentPct
LOD: {FIXED [Geo],[Year]: MEDIAN([Income])}, {FIXED [Geo],[Year]: MEDIAN([Home Price])}
Indexed: 100*SUM([Value]) / WINDOW_MIN(IF [Year]=[pBaselineYear] THEN SUM([Value]) END)
YoY: (SUM([Value]) - LOOKUP(SUM([Value]),-1))/ABS(LOOKUP(SUM([Value]),-1))
Affordability: MonthlyPayment/(Income/12); Flag if > 0.30
