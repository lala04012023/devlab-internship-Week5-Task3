* Dataset 294478 sətir, 5 sütundan ibarətdir
* ~147k control, ~147k treatment – qruplar balanslaşdırılmışdır
* 3894 sətir misassignment var (group vs landing_page uyğunsuzluğu) – silindi
* Control conversion rate: 12.04%
* Treatment conversion rate: 11.88%
* Fərq: -0.16 percentage point (yeni səhifə daha az convert edir)
* Günlər üzrə conversion rate sabitdir – temporal bias yoxdur
* Nəticə: yeni dizayn köhnəni üstələmir


---------------------------------------------------------------
* The dataset contains **294,478 rows and 5 columns**.
* Approximately **147K users are in the control group and 147K in the treatment group**, indicating that the groups are well balanced.
* There are **3,894 misassigned users** where the `group` and `landing_page` do not match. These rows were removed.
* **Control conversion rate: 12.04%**
* **Treatment conversion rate: 11.88%**
* **Difference: -0.16 percentage points**, meaning the new landing page performs slightly worse than the existing one.
* Conversion rates remain relatively stable across days, indicating **no significant temporal bias**.
* **Conclusion:** The new design does not outperform the existing design and should not be adopted based on the current A/B test results.
