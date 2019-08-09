---
title: "Veteran Population Data for the 41st Congression District"
output: 
  pdf_document:
    toc: true
---


```r
#install.packages("readxl")
#install.packages("kableExtra")
#install.packages("ggplot2")
#install.packages("sp")
#install.packages("gghighlight")
#tinytex::install_tinytex()
```
# Veteran Overview
In general this doucment with outlines the history of VA facilities in the area, Veteran Needs and demographics, as well as the Capacity, Quality, and Accesibility of nearby CBOCs and VA Medical Centers.


# History - 
In the 1970's the current VA's were established around Riverside. Jerry Lewis, Rep for Redlands, was on the appropriations committee.

# Veteran Population and Needs in Riverside County

This data is the US census data from 2017 showing current breakdown of Veteran Population in Riverside County. We have a total of 140,000 veterans making up about 8% of the population. 

\begin{figure}
\includegraphics[width=1\linewidth]{vet_map} \caption{Veterans in Riverside County}\label{fig:pressure}
\end{figure}


\begin{figure}
\includegraphics[width=1\linewidth]{drive time} \caption{Veterans in Riverside County}\label{fig:unnamed-chunk-2}
\end{figure}
\begin{figure}
\includegraphics[width=1\linewidth]{vet_map} \caption{Veterans in Riverside County}\label{fig:unnamed-chunk-3}
\end{figure}
\begin{figure}
\includegraphics[width=1\linewidth]{Poverty_vet} \caption{Veterans in Riverside County}\label{fig:unnamed-chunk-4}
\end{figure}
\begin{figure}
\includegraphics[width=1\linewidth]{vet_map} \caption{Veterans in Riverside County}\label{fig:unnamed-chunk-5}
\end{figure}

\begin{figure}
\includegraphics[width=1\linewidth]{legend} \caption{Veterans in Riverside County}\label{fig:unnamed-chunk-6}
\end{figure}

\begin{table}[H]
\centering
\begin{tabular}{l|r}
\hline
Male: - 18 to 64 years: - In Armed Forces & 2106\\
\hline
Male: - 18 to 64 years: - Civilian: - Veteran & 78233\\
\hline
Male: - 65 years and over: - Civilian: - Veteran & 57718\\
\hline
Female: - 18 to 64 years: - In Armed Forces & 310\\
\hline
Female: - 18 to 64 years: - Civilian: - Veteran & 5514\\
\hline
Female: - 65 years and over: - Civilian: - Veteran & 2709\\
\hline
\end{tabular}
\end{table}

![](vet-data_files/figure-latex/unnamed-chunk-7-1.pdf)<!-- --> 



\begin{table}[H]
\centering
\begin{tabular}{l|l|l|l|r|r|r|r|r}
\hline
Code & Age & Disability & Location & Margin of Error & Population & Percent Affected & Error & Total Population\\
\hline
HD01\_VD51 & 65+ years & No disability & Congressional District 36 & 607 & 1359 & 0.2210615 & 0.0987376 & 614761\\
\hline
HD01\_VD51 & 65+ years & No disability & Congressional District 04 & 499 & 1148 & 0.1933470 & 0.0840420 & 593751\\
\hline
HD01\_VD21 & 35 to 54 years & No disability & Congressional District 23 & 535 & 963 & 0.1923534 & 0.1068630 & 500641\\
\hline
HD01\_VD21 & 35 to 54 years & No disability & Congressional District 53 & 707 & 1041 & 0.1886765 & 0.1281405 & 551738\\
\hline
HD01\_VD06 & 18 to 34 years & No disability & Congressional District 23 & 632 & 832 & 0.1661869 & 0.1262382 & 500641\\
\hline
HD01\_VD51 & 65+ years & No disability & Congressional District 01 & 406 & 889 & 0.1601294 & 0.0731300 & 555176\\
\hline
HD01\_VD50 & 65+ years & With a disability & Congressional District 43 & 530 & 867 & 0.1572364 & 0.0961191 & 551399\\
\hline
HD01\_VD35 & 55 to 64 years & With a disability & Congressional District 12 & 720 & 908 & 0.1560333 & 0.1237269 & 581927\\
\hline
HD01\_VD50 & 65+ years & With a disability & Congressional District 11 & 635 & 848 & 0.1541636 & 0.1154409 & 550065\\
\hline
HD01\_VD21 & 35 to 54 years & No disability & Congressional District 06 & 562 & 860 & 0.1523872 & 0.0995832 & 564352\\
\hline
HD01\_VD51 & 65+ years & No disability & Congressional District 47 & 403 & 888 & 0.1516663 & 0.0688305 & 585496\\
\hline
HD01\_VD50 & 65+ years & With a disability & Congressional District 01 & 341 & 837 & 0.1507630 & 0.0614220 & 555176\\
\hline
HD01\_VD36 & 55 to 64 years & No disability & Congressional District 47 & 562 & 882 & 0.1506415 & 0.0959870 & 585496\\
\hline
HD01\_VD21 & 35 to 54 years & No disability & Congressional District 05 & 591 & 862 & 0.1434670 & 0.0983631 & 600835\\
\hline
HD01\_VD36 & 55 to 64 years & No disability & Congressional District 37 & 498 & 755 & 0.1388805 & 0.0916059 & 543633\\
\hline
HD01\_VD50 & 65+ years & With a disability & Congressional District 24 & 409 & 821 & 0.1361539 & 0.0678282 & 602994\\
\hline
HD01\_VD35 & 55 to 64 years & With a disability & Congressional District 31 & 577 & 714 & 0.1361045 & 0.1099892 & 524597\\
\hline
HD01\_VD21 & 35 to 54 years & No disability & Congressional District 01 & 466 & 716 & 0.1289681 & 0.0839373 & 555176\\
\hline
HD01\_VD50 & 65+ years & With a disability & Congressional District 23 & 356 & 644 & 0.1286351 & 0.0711088 & 500641\\
\hline
HD01\_VD50 & 65+ years & With a disability & Congressional District 04 & 475 & 741 & 0.1247998 & 0.0799999 & 593751\\
\hline
HD01\_VD21 & 35 to 54 years & No disability & Congressional District 07 & 918 & 637 & 0.1226288 & 0.1767240 & 519454\\
\hline
HD01\_VD21 & 35 to 54 years & No disability & Congressional District 25 & 518 & 696 & 0.1221173 & 0.0908861 & 569944\\
\hline
HD01\_VD51 & 65+ years & No disability & Congressional District 18 & 452 & 671 & 0.1218779 & 0.0820996 & 550551\\
\hline
HD01\_VD50 & 65+ years & With a disability & Congressional District 08 & 352 & 717 & 0.1215617 & 0.0596788 & 589824\\
\hline
HD01\_VD51 & 65+ years & No disability & Congressional District 03 & 532 & 642 & 0.1215536 & 0.1007267 & 528162\\
\hline
HD01\_VD50 & 65+ years & With a disability & Congressional District 31 & 409 & 619 & 0.1179953 & 0.0779646 & 524597\\
\hline
HD01\_VD35 & 55 to 64 years & With a disability & Congressional District 37 & 507 & 640 & 0.1177265 & 0.0932614 & 543633\\
\hline
HD01\_VD50 & 65+ years & With a disability & Congressional District 16 & 433 & 595 & 0.1176131 & 0.0855907 & 505896\\
\hline
HD01\_VD51 & 65+ years & No disability & Congressional District 53 & 421 & 645 & 0.1169033 & 0.0763043 & 551738\\
\hline
HD01\_VD51 & 65+ years & No disability & Congressional District 30 & 398 & 645 & 0.1164493 & 0.0718556 & 553889\\
\hline
HD01\_VD51 & 65+ years & No disability & Congressional District 08 & 480 & 682 & 0.1156277 & 0.0813802 & 589824\\
\hline
HD01\_VD35 & 55 to 64 years & With a disability & Congressional District 13 & 508 & 661 & 0.1148261 & 0.0882476 & 575653\\
\hline
HD01\_VD51 & 65+ years & No disability & Congressional District 07 & 286 & 594 & 0.1143508 & 0.0550578 & 519454\\
\hline
HD01\_VD35 & 55 to 64 years & With a disability & Congressional District 16 & 393 & 571 & 0.1128690 & 0.0776840 & 505896\\
\hline
HD01\_VD50 & 65+ years & With a disability & Congressional District 53 & 406 & 618 & 0.1120097 & 0.0735857 & 551738\\
\hline
HD01\_VD06 & 18 to 34 years & No disability & Congressional District 49 & 597 & 574 & 0.1117532 & 0.1162311 & 513632\\
\hline
HD01\_VD50 & 65+ years & With a disability & Congressional District 37 & 391 & 599 & 0.1101846 & 0.0719235 & 543633\\
\hline
HD01\_VD50 & 65+ years & With a disability & Congressional District 28 & 322 & 513 & 0.1095508 & 0.0687629 & 468276\\
\hline
HD01\_VD51 & 65+ years & No disability & Congressional District 52 & 324 & 623 & 0.1085481 & 0.0564520 & 573939\\
\hline
HD01\_VD50 & 65+ years & With a disability & Congressional District 05 & 325 & 623 & 0.1036890 & 0.0540914 & 600835\\
\hline
HD01\_VD35 & 55 to 64 years & With a disability & Congressional District 23 & 381 & 518 & 0.1034674 & 0.0761024 & 500641\\
\hline
HD01\_VD21 & 35 to 54 years & No disability & Congressional District 50 & 453 & 559 & 0.1025681 & 0.0831187 & 545004\\
\hline
HD01\_VD51 & 65+ years & No disability & Congressional District 34 & 326 & 623 & 0.1025369 & 0.0536550 & 607586\\
\hline
HD01\_VD51 & 65+ years & No disability & Congressional District 38 & 260 & 571 & 0.1023653 & 0.0466112 & 557806\\
\hline
HD01\_VD36 & 55 to 64 years & No disability & Congressional District 13 & 550 & 589 & 0.1023186 & 0.0955437 & 575653\\
\hline
HD01\_VD50 & 65+ years & With a disability & Congressional District 27 & 449 & 538 & 0.1007081 & 0.0840482 & 534217\\
\hline
HD01\_VD50 & 65+ years & With a disability & Congressional District 02 & 521 & 654 & 0.0985416 & 0.0785018 & 663679\\
\hline
HD01\_VD36 & 55 to 64 years & No disability & Congressional District 49 & 625 & 506 & 0.0985141 & 0.1216824 & 513632\\
\hline
HD01\_VD21 & 35 to 54 years & No disability & Congressional District 20 & 610 & 591 & 0.0979520 & 0.1011010 & 603357\\
\hline
HD01\_VD06 & 18 to 34 years & No disability & Congressional District 34 & 385 & 591 & 0.0972702 & 0.0633655 & 607586\\
\hline
HD01\_VD51 & 65+ years & No disability & Congressional District 25 & 368 & 543 & 0.0952725 & 0.0645677 & 569944\\
\hline
HD01\_VD21 & 35 to 54 years & No disability & Congressional District 12 & 446 & 554 & 0.0952009 & 0.0766419 & 581927\\
\hline
HD01\_VD50 & 65+ years & With a disability & Congressional District 12 & 370 & 554 & 0.0952009 & 0.0635819 & 581927\\
\hline
HD01\_VD51 & 65+ years & No disability & Congressional District 50 & 417 & 518 & 0.0950452 & 0.0765132 & 545004\\
\hline
HD01\_VD51 & 65+ years & No disability & Congressional District 27 & 358 & 506 & 0.0947181 & 0.0670140 & 534217\\
\hline
HD01\_VD06 & 18 to 34 years & No disability & Congressional District 50 & 314 & 512 & 0.0939443 & 0.0576143 & 545004\\
\hline
HD01\_VD50 & 65+ years & With a disability & Congressional District 36 & 361 & 573 & 0.0932070 & 0.0587220 & 614761\\
\hline
HD01\_VD21 & 35 to 54 years & No disability & Congressional District 13 & 306 & 535 & 0.0929379 & 0.0531570 & 575653\\
\hline
HD01\_VD21 & 35 to 54 years & No disability & Congressional District 52 & 430 & 532 & 0.0926928 & 0.0749209 & 573939\\
\hline
HD01\_VD06 & 18 to 34 years & No disability & Congressional District 16 & 526 & 460 & 0.0909278 & 0.1039739 & 505896\\
\hline
HD01\_VD36 & 55 to 64 years & No disability & Congressional District 20 & 422 & 537 & 0.0890020 & 0.0699420 & 603357\\
\hline
HD01\_VD20 & 35 to 54 years & With a disability & Congressional District 01 & 356 & 492 & 0.0886205 & 0.0641238 & 555176\\
\hline
HD01\_VD21 & 35 to 54 years & No disability & Congressional District 45 & 367 & 461 & 0.0883865 & 0.0703641 & 521573\\
\hline
HD01\_VD35 & 55 to 64 years & With a disability & Congressional District 47 & 346 & 516 & 0.0881304 & 0.0590952 & 585496\\
\hline
HD01\_VD06 & 18 to 34 years & No disability & Congressional District 06 & 414 & 496 & 0.0878884 & 0.0733585 & 564352\\
\hline
HD01\_VD36 & 55 to 64 years & No disability & Congressional District 06 & 293 & 495 & 0.0877112 & 0.0519180 & 564352\\
\hline
HD01\_VD06 & 18 to 34 years & No disability & Congressional District 43 & 406 & 480 & 0.0870513 & 0.0736309 & 551399\\
\hline
HD01\_VD21 & 35 to 54 years & No disability & Congressional District 08 & 362 & 510 & 0.0864665 & 0.0613742 & 589824\\
\hline
HD01\_VD21 & 35 to 54 years & No disability & Congressional District 33 & 551 & 494 & 0.0863747 & 0.0963410 & 571927\\
\hline
HD01\_VD50 & 65+ years & With a disability & Congressional District 45 & 305 & 447 & 0.0857023 & 0.0584770 & 521573\\
\hline
HD01\_VD36 & 55 to 64 years & No disability & Congressional District 45 & 398 & 446 & 0.0855106 & 0.0763076 & 521573\\
\hline
HD01\_VD50 & 65+ years & With a disability & Congressional District 22 & 354 & 511 & 0.0854147 & 0.0591718 & 598258\\
\hline
HD01\_VD50 & 65+ years & With a disability & Congressional District 38 & 349 & 469 & 0.0840794 & 0.0625666 & 557806\\
\hline
HD01\_VD51 & 65+ years & No disability & Congressional District 05 & 341 & 500 & 0.0832175 & 0.0567544 & 600835\\
\hline
HD01\_VD21 & 35 to 54 years & No disability & Congressional District 03 & 361 & 438 & 0.0829291 & 0.0683502 & 528162\\
\hline
HD01\_VD06 & 18 to 34 years & No disability & Congressional District 03 & 348 & 434 & 0.0821718 & 0.0658889 & 528162\\
\hline
HD01\_VD21 & 35 to 54 years & No disability & Congressional District 51 & 293 & 460 & 0.0815898 & 0.0519692 & 563796\\
\hline
HD01\_VD51 & 65+ years & No disability & Congressional District 48 & 330 & 457 & 0.0813822 & 0.0587661 & 561548\\
\hline
HD01\_VD51 & 65+ years & No disability & Congressional District 10 & 334 & 454 & 0.0809054 & 0.0595207 & 561149\\
\hline
HD01\_VD51 & 65+ years & No disability & Congressional District 26 & 226 & 470 & 0.0805948 & 0.0387541 & 583164\\
\hline
HD01\_VD50 & 65+ years & With a disability & Congressional District 49 & 475 & 412 & 0.0802131 & 0.0924787 & 513632\\
\hline
HD01\_VD50 & 65+ years & With a disability & Congressional District 47 & 363 & 457 & 0.0780535 & 0.0619987 & 585496\\
\hline
HD01\_VD51 & 65+ years & No disability & Congressional District 32 & 252 & 428 & 0.0779118 & 0.0458733 & 549339\\
\hline
HD01\_VD50 & 65+ years & With a disability & Congressional District 52 & 290 & 446 & 0.0777086 & 0.0505280 & 573939\\
\hline
HD01\_VD50 & 65+ years & With a disability & Congressional District 17 & 426 & 430 & 0.0776163 & 0.0768943 & 554007\\
\hline
HD01\_VD50 & 65+ years & With a disability & Congressional District 10 & 236 & 433 & 0.0771631 & 0.0420566 & 561149\\
\hline
HD01\_VD36 & 55 to 64 years & No disability & Congressional District 01 & 272 & 428 & 0.0770927 & 0.0489935 & 555176\\
\hline
HD01\_VD50 & 65+ years & With a disability & Congressional District 41 & 324 & 443 & 0.0770199 & 0.0563306 & 575176\\
\hline
HD01\_VD51 & 65+ years & No disability & Congressional District 37 & 353 & 418 & 0.0768901 & 0.0649335 & 543633\\
\hline
HD01\_VD51 & 65+ years & No disability & Congressional District 13 & 331 & 440 & 0.0764349 & 0.0574999 & 575653\\
\hline
HD01\_VD51 & 65+ years & No disability & Congressional District 02 & 428 & 504 & 0.0759403 & 0.0644890 & 663679\\
\hline
HD01\_VD51 & 65+ years & No disability & Congressional District 06 & 244 & 428 & 0.0758392 & 0.0432354 & 564352\\
\hline
HD01\_VD36 & 55 to 64 years & No disability & Congressional District 36 & 396 & 461 & 0.0749885 & 0.0644153 & 614761\\
\hline
HD01\_VD36 & 55 to 64 years & No disability & Congressional District 44 & 410 & 425 & 0.0748788 & 0.0722360 & 567584\\
\hline
HD01\_VD36 & 55 to 64 years & No disability & Congressional District 08 & 271 & 436 & 0.0739204 & 0.0459459 & 589824\\
\hline
HD01\_VD35 & 55 to 64 years & With a disability & Congressional District 01 & 258 & 410 & 0.0738505 & 0.0464717 & 555176\\
\hline
HD01\_VD50 & 65+ years & With a disability & Congressional District 26 & 354 & 429 & 0.0735642 & 0.0607033 & 583164\\
\hline
HD01\_VD36 & 55 to 64 years & No disability & Congressional District 16 & 190 & 372 & 0.0735329 & 0.0375571 & 505896\\
\hline
HD01\_VD35 & 55 to 64 years & With a disability & Congressional District 44 & 438 & 417 & 0.0734693 & 0.0771692 & 567584\\
\hline
HD01\_VD51 & 65+ years & No disability & Congressional District 51 & 230 & 413 & 0.0732534 & 0.0407949 & 563796\\
\hline
HD01\_VD21 & 35 to 54 years & No disability & Congressional District 43 & 314 & 402 & 0.0729055 & 0.0569461 & 551399\\
\hline
HD01\_VD06 & 18 to 34 years & No disability & Congressional District 45 & 272 & 380 & 0.0728565 & 0.0521499 & 521573\\
\hline
HD01\_VD50 & 65+ years & With a disability & Congressional District 06 & 267 & 407 & 0.0721181 & 0.0473109 & 564352\\
\hline
HD01\_VD36 & 55 to 64 years & No disability & Congressional District 42 & 464 & 410 & 0.0719442 & 0.0814198 & 569886\\
\hline
HD01\_VD50 & 65+ years & With a disability & Congressional District 42 & 254 & 407 & 0.0714178 & 0.0445703 & 569886\\
\hline
HD01\_VD21 & 35 to 54 years & No disability & Congressional District 46 & 423 & 390 & 0.0712151 & 0.0772409 & 547637\\
\hline
HD01\_VD50 & 65+ years & With a disability & Congressional District 44 & 283 & 403 & 0.0710027 & 0.0498605 & 567584\\
\hline
HD01\_VD20 & 35 to 54 years & With a disability & Congressional District 42 & 301 & 401 & 0.0703650 & 0.0528176 & 569886\\
\hline
HD01\_VD50 & 65+ years & With a disability & Congressional District 50 & 258 & 383 & 0.0702747 & 0.0473391 & 545004\\
\hline
HD01\_VD20 & 35 to 54 years & With a disability & Congressional District 34 & 450 & 425 & 0.0699489 & 0.0740636 & 607586\\
\hline
HD01\_VD50 & 65+ years & With a disability & Congressional District 03 & 226 & 363 & 0.0687289 & 0.0427899 & 528162\\
\hline
HD01\_VD36 & 55 to 64 years & No disability & Congressional District 31 & 427 & 356 & 0.0678616 & 0.0813958 & 524597\\
\hline
HD01\_VD51 & 65+ years & No disability & Congressional District 24 & 211 & 404 & 0.0669990 & 0.0349921 & 602994\\
\hline
HD01\_VD06 & 18 to 34 years & No disability & Congressional District 07 & 268 & 347 & 0.0668009 & 0.0515926 & 519454\\
\hline
HD01\_VD36 & 55 to 64 years & No disability & Congressional District 53 & 351 & 367 & 0.0665171 & 0.0636172 & 551738\\
\hline
HD01\_VD50 & 65+ years & With a disability & Congressional District 33 & 338 & 380 & 0.0664420 & 0.0590985 & 571927\\
\hline
HD01\_VD36 & 55 to 64 years & No disability & Congressional District 43 & 497 & 366 & 0.0663766 & 0.0901344 & 551399\\
\hline
HD01\_VD36 & 55 to 64 years & No disability & Congressional District 40 & 312 & 342 & 0.0650491 & 0.0593430 & 525757\\
\hline
HD01\_VD06 & 18 to 34 years & No disability & Congressional District 52 & 303 & 372 & 0.0648153 & 0.0527931 & 573939\\
\hline
HD01\_VD21 & 35 to 54 years & No disability & Congressional District 31 & 288 & 340 & 0.0648117 & 0.0548993 & 524597\\
\hline
HD01\_VD06 & 18 to 34 years & No disability & Congressional District 01 & 307 & 358 & 0.0644841 & 0.0552978 & 555176\\
\hline
HD01\_VD35 & 55 to 64 years & With a disability & Congressional District 06 & 261 & 360 & 0.0637900 & 0.0462477 & 564352\\
\hline
HD01\_VD51 & 65+ years & No disability & Congressional District 40 & 192 & 333 & 0.0633372 & 0.0365188 & 525757\\
\hline
HD01\_VD36 & 55 to 64 years & No disability & Congressional District 03 & 317 & 332 & 0.0628595 & 0.0600195 & 528162\\
\hline
HD01\_VD51 & 65+ years & No disability & Congressional District 09 & 258 & 375 & 0.0625339 & 0.0430233 & 599675\\
\hline
HD01\_VD36 & 55 to 64 years & No disability & Congressional District 51 & 320 & 351 & 0.0622566 & 0.0567581 & 563796\\
\hline
HD01\_VD21 & 35 to 54 years & No disability & Congressional District 04 & 271 & 368 & 0.0619788 & 0.0456420 & 593751\\
\hline
HD01\_VD50 & 65+ years & With a disability & Congressional District 30 & 247 & 342 & 0.0617452 & 0.0445938 & 553889\\
\hline
HD01\_VD35 & 55 to 64 years & With a disability & Congressional District 22 & 342 & 369 & 0.0616791 & 0.0571660 & 598258\\
\hline
HD01\_VD35 & 55 to 64 years & With a disability & Congressional District 29 & 315 & 327 & 0.0615905 & 0.0593303 & 530926\\
\hline
HD01\_VD20 & 35 to 54 years & With a disability & Congressional District 08 & 374 & 362 & 0.0613742 & 0.0634087 & 589824\\
\hline
HD01\_VD36 & 55 to 64 years & No disability & Congressional District 38 & 267 & 341 & 0.0611324 & 0.0478661 & 557806\\
\hline
HD01\_VD06 & 18 to 34 years & No disability & Congressional District 51 & 291 & 343 & 0.0608376 & 0.0516144 & 563796\\
\hline
HD01\_VD21 & 35 to 54 years & No disability & Congressional District 02 & 334 & 400 & 0.0602701 & 0.0503255 & 663679\\
\hline
HD01\_VD35 & 55 to 64 years & With a disability & Congressional District 51 & 300 & 339 & 0.0601281 & 0.0532107 & 563796\\
\hline
HD01\_VD21 & 35 to 54 years & No disability & Congressional District 35 & 331 & 324 & 0.0591782 & 0.0604567 & 547499\\
\hline
HD01\_VD21 & 35 to 54 years & No disability & Congressional District 10 & 309 & 332 & 0.0591643 & 0.0550656 & 561149\\
\hline
HD01\_VD06 & 18 to 34 years & No disability & Congressional District 31 & 274 & 308 & 0.0587117 & 0.0522306 & 524597\\
\hline
HD01\_VD51 & 65+ years & No disability & Congressional District 11 & 276 & 322 & 0.0585385 & 0.0501759 & 550065\\
\hline
HD01\_VD51 & 65+ years & No disability & Congressional District 45 & 220 & 303 & 0.0580935 & 0.0421801 & 521573\\
\hline
HD01\_VD21 & 35 to 54 years & No disability & Congressional District 48 & 292 & 326 & 0.0580538 & 0.0519991 & 561548\\
\hline
HD01\_VD35 & 55 to 64 years & With a disability & Congressional District 02 & 301 & 382 & 0.0575579 & 0.0453533 & 663679\\
\hline
HD01\_VD51 & 65+ years & No disability & Congressional District 49 & 239 & 295 & 0.0574341 & 0.0465314 & 513632\\
\hline
HD01\_VD06 & 18 to 34 years & No disability & Congressional District 53 & 272 & 316 & 0.0572736 & 0.0492988 & 551738\\
\hline
HD01\_VD06 & 18 to 34 years & No disability & Congressional District 28 & 378 & 267 & 0.0570177 & 0.0807216 & 468276\\
\hline
HD01\_VD35 & 55 to 64 years & With a disability & Congressional District 53 & 285 & 312 & 0.0565486 & 0.0516550 & 551738\\
\hline
HD01\_VD21 & 35 to 54 years & No disability & Congressional District 26 & 262 & 328 & 0.0562449 & 0.0449273 & 583164\\
\hline
HD01\_VD50 & 65+ years & With a disability & Congressional District 46 & 407 & 308 & 0.0562416 & 0.0743193 & 547637\\
\hline
HD01\_VD51 & 65+ years & No disability & Congressional District 15 & 235 & 317 & 0.0554169 & 0.0410819 & 572028\\
\hline
HD01\_VD21 & 35 to 54 years & No disability & Congressional District 32 & 264 & 302 & 0.0549752 & 0.0480578 & 549339\\
\hline
HD01\_VD05 & 18 to 34 years & With a disability & Congressional District 53 & 314 & 303 & 0.0549174 & 0.0569111 & 551738\\
\hline
HD01\_VD06 & 18 to 34 years & No disability & Congressional District 13 & 235 & 313 & 0.0543730 & 0.0408232 & 575653\\
\hline
HD01\_VD51 & 65+ years & No disability & Congressional District 39 & 179 & 301 & 0.0542520 & 0.0322628 & 554818\\
\hline
HD01\_VD21 & 35 to 54 years & No disability & Congressional District 29 & 230 & 288 & 0.0542448 & 0.0433205 & 530926\\
\hline
HD01\_VD21 & 35 to 54 years & No disability & Congressional District 49 & 244 & 275 & 0.0535403 & 0.0475048 & 513632\\
\hline
HD01\_VD36 & 55 to 64 years & No disability & Congressional District 18 & 322 & 293 & 0.0532194 & 0.0584869 & 550551\\
\hline
HD01\_VD35 & 55 to 64 years & With a disability & Congressional District 48 & 405 & 298 & 0.0530676 & 0.0721221 & 561548\\
\hline
HD01\_VD35 & 55 to 64 years & With a disability & Congressional District 07 & 272 & 274 & 0.0527477 & 0.0523627 & 519454\\
\hline
HD01\_VD51 & 65+ years & No disability & Congressional District 46 & 243 & 283 & 0.0516766 & 0.0443725 & 547637\\
\hline
HD01\_VD21 & 35 to 54 years & No disability & Congressional District 16 & 197 & 259 & 0.0511963 & 0.0389408 & 505896\\
\hline
HD01\_VD20 & 35 to 54 years & With a disability & Congressional District 23 & 274 & 256 & 0.0511344 & 0.0547298 & 500641\\
\hline
HD01\_VD36 & 55 to 64 years & No disability & Congressional District 30 & 270 & 280 & 0.0505516 & 0.0487462 & 553889\\
\hline
HD01\_VD50 & 65+ years & With a disability & Congressional District 25 & 267 & 288 & 0.0505313 & 0.0468467 & 569944\\
\hline
HD01\_VD36 & 55 to 64 years & No disability & Congressional District 48 & 237 & 282 & 0.0502183 & 0.0422048 & 561548\\
\hline
HD01\_VD21 & 35 to 54 years & No disability & Congressional District 37 & 227 & 273 & 0.0502177 & 0.0417561 & 543633\\
\hline
HD01\_VD51 & 65+ years & No disability & Congressional District 16 & 265 & 254 & 0.0502079 & 0.0523823 & 505896\\
\hline
HD01\_VD36 & 55 to 64 years & No disability & Congressional District 07 & 274 & 260 & 0.0500526 & 0.0527477 & 519454\\
\hline
HD01\_VD21 & 35 to 54 years & No disability & Congressional District 47 & 216 & 290 & 0.0495307 & 0.0368918 & 585496\\
\hline
HD01\_VD50 & 65+ years & With a disability & Congressional District 35 & 202 & 270 & 0.0493152 & 0.0368950 & 547499\\
\hline
HD01\_VD35 & 55 to 64 years & With a disability & Congressional District 36 & 281 & 300 & 0.0487995 & 0.0457088 & 614761\\
\hline
HD01\_VD20 & 35 to 54 years & With a disability & Congressional District 53 & 275 & 268 & 0.0485738 & 0.0498425 & 551738\\
\hline
HD01\_VD20 & 35 to 54 years & With a disability & Congressional District 36 & 375 & 298 & 0.0484741 & 0.0609993 & 614761\\
\hline
HD01\_VD05 & 18 to 34 years & With a disability & Congressional District 36 & 481 & 297 & 0.0483115 & 0.0782418 & 614761\\
\hline
HD01\_VD35 & 55 to 64 years & With a disability & Congressional District 41 & 210 & 276 & 0.0479853 & 0.0365106 & 575176\\
\hline
HD01\_VD51 & 65+ years & No disability & Congressional District 43 & 304 & 263 & 0.0476969 & 0.0551325 & 551399\\
\hline
HD01\_VD35 & 55 to 64 years & With a disability & Congressional District 08 & 275 & 280 & 0.0474718 & 0.0466241 & 589824\\
\hline
HD01\_VD06 & 18 to 34 years & No disability & Congressional District 22 & 217 & 283 & 0.0473040 & 0.0362720 & 598258\\
\hline
HD01\_VD51 & 65+ years & No disability & Congressional District 35 & 213 & 258 & 0.0471234 & 0.0389042 & 547499\\
\hline
HD01\_VD50 & 65+ years & With a disability & Congressional District 07 & 185 & 244 & 0.0469724 & 0.0356143 & 519454\\
\hline
HD01\_VD06 & 18 to 34 years & No disability & Congressional District 41 & 314 & 269 & 0.0467683 & 0.0545920 & 575176\\
\hline
HD01\_VD20 & 35 to 54 years & With a disability & Congressional District 22 & 392 & 278 & 0.0464682 & 0.0655236 & 598258\\
\hline
HD01\_VD50 & 65+ years & With a disability & Congressional District 21 & 250 & 277 & 0.0462229 & 0.0417174 & 599270\\
\hline
HD01\_VD21 & 35 to 54 years & No disability & Congressional District 11 & 211 & 251 & 0.0456310 & 0.0383591 & 550065\\
\hline
HD01\_VD51 & 65+ years & No disability & Congressional District 42 & 239 & 260 & 0.0456232 & 0.0419382 & 569886\\
\hline
HD01\_VD06 & 18 to 34 years & No disability & Congressional District 42 & 292 & 259 & 0.0454477 & 0.0512383 & 569886\\
\hline
HD01\_VD06 & 18 to 34 years & No disability & Congressional District 38 & 334 & 249 & 0.0446392 & 0.0598774 & 557806\\
\hline
HD01\_VD35 & 55 to 64 years & With a disability & Congressional District 25 & 181 & 253 & 0.0443903 & 0.0317575 & 569944\\
\hline
HD01\_VD20 & 35 to 54 years & With a disability & Congressional District 31 & 234 & 232 & 0.0442244 & 0.0446057 & 524597\\
\hline
HD01\_VD50 & 65+ years & With a disability & Congressional District 51 & 189 & 249 & 0.0441649 & 0.0335228 & 563796\\
\hline
HD01\_VD20 & 35 to 54 years & With a disability & Congressional District 51 & 251 & 247 & 0.0438102 & 0.0445196 & 563796\\
\hline
HD01\_VD20 & 35 to 54 years & With a disability & Congressional District 49 & 220 & 225 & 0.0438057 & 0.0428322 & 513632\\
\hline
HD01\_VD36 & 55 to 64 years & No disability & Congressional District 46 & 290 & 239 & 0.0436420 & 0.0529548 & 547637\\
\hline
HD01\_VD05 & 18 to 34 years & With a disability & Congressional District 28 & 240 & 204 & 0.0435641 & 0.0512518 & 468276\\
\hline
HD01\_VD51 & 65+ years & No disability & Congressional District 41 & 181 & 248 & 0.0431172 & 0.0314686 & 575176\\
\hline
HD01\_VD36 & 55 to 64 years & No disability & Congressional District 09 & 246 & 258 & 0.0430233 & 0.0410222 & 599675\\
\hline
HD01\_VD20 & 35 to 54 years & With a disability & Congressional District 16 & 216 & 217 & 0.0428942 & 0.0426965 & 505896\\
\hline
HD01\_VD20 & 35 to 54 years & With a disability & Congressional District 06 & 265 & 242 & 0.0428810 & 0.0469565 & 564352\\
\hline
HD01\_VD35 & 55 to 64 years & With a disability & Congressional District 03 & 222 & 226 & 0.0427899 & 0.0420326 & 528162\\
\hline
HD01\_VD50 & 65+ years & With a disability & Congressional District 18 & 208 & 230 & 0.0417763 & 0.0377803 & 550551\\
\hline
HD01\_VD51 & 65+ years & No disability & Congressional District 28 & 165 & 195 & 0.0416421 & 0.0352356 & 468276\\
\hline
HD01\_VD51 & 65+ years & No disability & Congressional District 20 & 214 & 249 & 0.0412691 & 0.0354682 & 603357\\
\hline
HD01\_VD50 & 65+ years & With a disability & Congressional District 19 & 237 & 242 & 0.0410767 & 0.0402280 & 589142\\
\hline
HD01\_VD21 & 35 to 54 years & No disability & Congressional District 18 & 211 & 225 & 0.0408681 & 0.0383252 & 550551\\
\hline
HD01\_VD21 & 35 to 54 years & No disability & Congressional District 27 & 196 & 217 & 0.0406202 & 0.0366892 & 534217\\
\hline
HD01\_VD36 & 55 to 64 years & No disability & Congressional District 52 & 251 & 233 & 0.0405966 & 0.0437329 & 573939\\
\hline
HD01\_VD51 & 65+ years & No disability & Congressional District 33 & 167 & 231 & 0.0403898 & 0.0291995 & 571927\\
\hline
HD01\_VD36 & 55 to 64 years & No disability & Congressional District 10 & 254 & 225 & 0.0400963 & 0.0452643 & 561149\\
\hline
HD01\_VD20 & 35 to 54 years & With a disability & Congressional District 26 & 256 & 231 & 0.0396115 & 0.0438985 & 583164\\
\hline
HD01\_VD36 & 55 to 64 years & No disability & Congressional District 28 & 195 & 185 & 0.0395066 & 0.0416421 & 468276\\
\hline
HD01\_VD36 & 55 to 64 years & No disability & Congressional District 50 & 192 & 213 & 0.0390823 & 0.0352291 & 545004\\
\hline
HD01\_VD21 & 35 to 54 years & No disability & Congressional District 28 & 201 & 183 & 0.0390795 & 0.0429234 & 468276\\
\hline
HD01\_VD36 & 55 to 64 years & No disability & Congressional District 29 & 153 & 206 & 0.0388001 & 0.0288176 & 530926\\
\hline
HD01\_VD36 & 55 to 64 years & No disability & Congressional District 11 & 246 & 211 & 0.0383591 & 0.0447220 & 550065\\
\hline
HD01\_VD06 & 18 to 34 years & No disability & Congressional District 48 & 166 & 215 & 0.0382870 & 0.0295611 & 561548\\
\hline
HD01\_VD36 & 55 to 64 years & No disability & Congressional District 35 & 154 & 209 & 0.0381736 & 0.0281279 & 547499\\
\hline
HD01\_VD36 & 55 to 64 years & No disability & Congressional District 14 & 181 & 216 & 0.0378148 & 0.0316874 & 571205\\
\hline
HD01\_VD06 & 18 to 34 years & No disability & Congressional District 47 & 203 & 221 & 0.0377458 & 0.0346715 & 585496\\
\hline
HD01\_VD36 & 55 to 64 years & No disability & Congressional District 23 & 189 & 188 & 0.0375519 & 0.0377516 & 500641\\
\hline
HD01\_VD21 & 35 to 54 years & No disability & Congressional District 34 & 185 & 223 & 0.0367026 & 0.0304484 & 607586\\
\hline
HD01\_VD36 & 55 to 64 years & No disability & Congressional District 21 & 237 & 217 & 0.0362107 & 0.0395481 & 599270\\
\hline
HD01\_VD51 & 65+ years & No disability & Congressional District 31 & 222 & 185 & 0.0352652 & 0.0423182 & 524597\\
\hline
HD01\_VD36 & 55 to 64 years & No disability & Congressional District 02 & 259 & 234 & 0.0352580 & 0.0390249 & 663679\\
\hline
HD01\_VD06 & 18 to 34 years & No disability & Congressional District 26 & 304 & 203 & 0.0348101 & 0.0521294 & 583164\\
\hline
HD01\_VD20 & 35 to 54 years & With a disability & Congressional District 07 & 151 & 180 & 0.0346518 & 0.0290690 & 519454\\
\hline
HD01\_VD20 & 35 to 54 years & With a disability & Congressional District 50 & 235 & 184 & 0.0337612 & 0.0431189 & 545004\\
\hline
HD01\_VD06 & 18 to 34 years & No disability & Congressional District 27 & 208 & 178 & 0.0333198 & 0.0389355 & 534217\\
\hline
HD01\_VD35 & 55 to 64 years & With a disability & Congressional District 28 & 171 & 155 & 0.0331001 & 0.0365169 & 468276\\
\hline
HD01\_VD35 & 55 to 64 years & With a disability & Congressional District 40 & 204 & 172 & 0.0327147 & 0.0388012 & 525757\\
\hline
HD01\_VD50 & 65+ years & With a disability & Congressional District 09 & 207 & 196 & 0.0326844 & 0.0345187 & 599675\\
\hline
HD01\_VD35 & 55 to 64 years & With a disability & Congressional District 32 & 164 & 178 & 0.0324026 & 0.0298541 & 549339\\
\hline
HD01\_VD36 & 55 to 64 years & No disability & Congressional District 39 & 158 & 179 & 0.0322628 & 0.0284778 & 554818\\
\hline
HD01\_VD06 & 18 to 34 years & No disability & Congressional District 08 & 210 & 189 & 0.0320435 & 0.0356038 & 589824\\
\hline
HD01\_VD21 & 35 to 54 years & No disability & Congressional District 24 & 207 & 193 & 0.0320070 & 0.0343287 & 602994\\
\hline
HD01\_VD35 & 55 to 64 years & With a disability & Congressional District 43 & 252 & 176 & 0.0319188 & 0.0457019 & 551399\\
\hline
HD01\_VD06 & 18 to 34 years & No disability & Congressional District 11 & 277 & 172 & 0.0312690 & 0.0503577 & 550065\\
\hline
HD01\_VD36 & 55 to 64 years & No disability & Congressional District 22 & 205 & 186 & 0.0310903 & 0.0342662 & 598258\\
\hline
HD01\_VD36 & 55 to 64 years & No disability & Congressional District 04 & 204 & 183 & 0.0308210 & 0.0343578 & 593751\\
\hline
HD01\_VD21 & 35 to 54 years & No disability & Congressional District 36 & 232 & 189 & 0.0307437 & 0.0377382 & 614761\\
\hline
HD01\_VD35 & 55 to 64 years & With a disability & Congressional District 24 & 212 & 185 & 0.0306802 & 0.0351579 & 602994\\
\hline
HD01\_VD06 & 18 to 34 years & No disability & Congressional District 09 & 295 & 181 & 0.0301830 & 0.0491933 & 599675\\
\hline
HD01\_VD06 & 18 to 34 years & No disability & Congressional District 33 & 187 & 171 & 0.0298989 & 0.0326965 & 571927\\
\hline
HD01\_VD20 & 35 to 54 years & With a disability & Congressional District 03 & 150 & 156 & 0.0295364 & 0.0284004 & 528162\\
\hline
HD01\_VD06 & 18 to 34 years & No disability & Congressional District 02 & 255 & 196 & 0.0295323 & 0.0384222 & 663679\\
\hline
HD01\_VD36 & 55 to 64 years & No disability & Congressional District 34 & 212 & 177 & 0.0291317 & 0.0348922 & 607586\\
\hline
HD01\_VD05 & 18 to 34 years & With a disability & Congressional District 01 & 279 & 160 & 0.0288197 & 0.0502543 & 555176\\
\hline
HD01\_VD51 & 65+ years & No disability & Congressional District 44 & 160 & 163 & 0.0287182 & 0.0281897 & 567584\\
\hline
HD01\_VD05 & 18 to 34 years & With a disability & Congressional District 44 & 257 & 160 & 0.0281897 & 0.0452796 & 567584\\
\hline
HD01\_VD05 & 18 to 34 years & With a disability & Congressional District 02 & 255 & 183 & 0.0275736 & 0.0384222 & 663679\\
\hline
HD01\_VD35 & 55 to 64 years & With a disability & Congressional District 18 & 199 & 151 & 0.0274271 & 0.0361456 & 550551\\
\hline
HD01\_VD35 & 55 to 64 years & With a disability & Congressional District 39 & 138 & 148 & 0.0266754 & 0.0248730 & 554818\\
\hline
HD01\_VD21 & 35 to 54 years & No disability & Congressional District 41 & 159 & 153 & 0.0266006 & 0.0276437 & 575176\\
\hline
HD01\_VD50 & 65+ years & With a disability & Congressional District 13 & 133 & 153 & 0.0265785 & 0.0231042 & 575653\\
\hline
HD01\_VD50 & 65+ years & With a disability & Congressional District 20 & 179 & 160 & 0.0265183 & 0.0296673 & 603357\\
\hline
HD01\_VD35 & 55 to 64 years & With a disability & Congressional District 46 & 156 & 145 & 0.0264774 & 0.0284860 & 547637\\
\hline
HD01\_VD21 & 35 to 54 years & No disability & Congressional District 17 & 171 & 146 & 0.0263535 & 0.0308660 & 554007\\
\hline
HD01\_VD51 & 65+ years & No disability & Congressional District 22 & 156 & 156 & 0.0260757 & 0.0260757 & 598258\\
\hline
HD01\_VD05 & 18 to 34 years & With a disability & Congressional District 24 & 236 & 157 & 0.0260367 & 0.0391380 & 602994\\
\hline
HD01\_VD35 & 55 to 64 years & With a disability & Congressional District 11 & 165 & 142 & 0.0258151 & 0.0299965 & 550065\\
\hline
HD01\_VD50 & 65+ years & With a disability & Congressional District 48 & 226 & 144 & 0.0256434 & 0.0402459 & 561548\\
\hline
HD01\_VD35 & 55 to 64 years & With a disability & Congressional District 04 & 161 & 152 & 0.0256000 & 0.0271157 & 593751\\
\hline
HD01\_VD20 & 35 to 54 years & With a disability & Congressional District 24 & 192 & 154 & 0.0255392 & 0.0318411 & 602994\\
\hline
HD01\_VD50 & 65+ years & With a disability & Congressional District 29 & 127 & 135 & 0.0254273 & 0.0239205 & 530926\\
\hline
HD01\_VD06 & 18 to 34 years & No disability & Congressional District 04 & 175 & 147 & 0.0247579 & 0.0294736 & 593751\\
\hline
HD01\_VD21 & 35 to 54 years & No disability & Congressional District 44 & 140 & 140 & 0.0246660 & 0.0246660 & 567584\\
\hline
HD01\_VD50 & 65+ years & With a disability & Congressional District 34 & 190 & 147 & 0.0241941 & 0.0312713 & 607586\\
\hline
HD01\_VD36 & 55 to 64 years & No disability & Congressional District 27 & 202 & 129 & 0.0241475 & 0.0378123 & 534217\\
\hline
HD01\_VD50 & 65+ years & With a disability & Congressional District 15 & 189 & 137 & 0.0239499 & 0.0330403 & 572028\\
\hline
HD01\_VD06 & 18 to 34 years & No disability & Congressional District 37 & 200 & 127 & 0.0233613 & 0.0367895 & 543633\\
\hline
HD01\_VD21 & 35 to 54 years & No disability & Congressional District 30 & 136 & 129 & 0.0232899 & 0.0245537 & 553889\\
\hline
HD01\_VD51 & 65+ years & No disability & Congressional District 14 & 143 & 133 & 0.0232841 & 0.0250348 & 571205\\
\hline
HD01\_VD35 & 55 to 64 years & With a disability & Congressional District 50 & 135 & 126 & 0.0231191 & 0.0247705 & 545004\\
\hline
HD01\_VD36 & 55 to 64 years & No disability & Congressional District 25 & 134 & 131 & 0.0229847 & 0.0235111 & 569944\\
\hline
HD01\_VD21 & 35 to 54 years & No disability & Congressional District 39 & 115 & 125 & 0.0225299 & 0.0207275 & 554818\\
\hline
HD01\_VD20 & 35 to 54 years & With a disability & Congressional District 05 & 118 & 135 & 0.0224687 & 0.0196393 & 600835\\
\hline
HD01\_VD06 & 18 to 34 years & No disability & Congressional District 46 & 149 & 122 & 0.0222775 & 0.0272078 & 547637\\
\hline
HD01\_VD06 & 18 to 34 years & No disability & Congressional District 14 & 167 & 126 & 0.0220586 & 0.0292364 & 571205\\
\hline
HD01\_VD35 & 55 to 64 years & With a disability & Congressional District 15 & 151 & 126 & 0.0220269 & 0.0263973 & 572028\\
\hline
HD01\_VD36 & 55 to 64 years & No disability & Congressional District 33 & 138 & 125 & 0.0218559 & 0.0241290 & 571927\\
\hline
HD01\_VD20 & 35 to 54 years & With a disability & Congressional District 52 & 186 & 125 & 0.0217793 & 0.0324076 & 573939\\
\hline
HD01\_VD50 & 65+ years & With a disability & Congressional District 14 & 285 & 124 & 0.0217085 & 0.0498945 & 571205\\
\hline
HD01\_VD36 & 55 to 64 years & No disability & Congressional District 41 & 121 & 124 & 0.0215586 & 0.0210370 & 575176\\
\hline
HD01\_VD35 & 55 to 64 years & With a disability & Congressional District 42 & 144 & 122 & 0.0214078 & 0.0252682 & 569886\\
\hline
HD01\_VD20 & 35 to 54 years & With a disability & Congressional District 43 & 177 & 118 & 0.0214001 & 0.0321002 & 551399\\
\hline
HD01\_VD21 & 35 to 54 years & No disability & Congressional District 19 & 122 & 125 & 0.0212173 & 0.0207081 & 589142\\
\hline
HD01\_VD51 & 65+ years & No disability & Congressional District 19 & 118 & 121 & 0.0205383 & 0.0200291 & 589142\\
\hline
HD01\_VD20 & 35 to 54 years & With a disability & Congressional District 41 & 140 & 117 & 0.0203416 & 0.0243404 & 575176\\
\hline
HD01\_VD36 & 55 to 64 years & No disability & Congressional District 19 & 149 & 119 & 0.0201989 & 0.0252910 & 589142\\
\hline
HD01\_VD20 & 35 to 54 years & With a disability & Congressional District 21 & 140 & 121 & 0.0201912 & 0.0233618 & 599270\\
\hline
HD01\_VD51 & 65+ years & No disability & Congressional District 29 & 117 & 107 & 0.0201535 & 0.0220370 & 530926\\
\hline
HD01\_VD06 & 18 to 34 years & No disability & Congressional District 21 & 181 & 119 & 0.0198575 & 0.0302034 & 599270\\
\hline
HD01\_VD50 & 65+ years & With a disability & Congressional District 32 & 108 & 108 & 0.0196600 & 0.0196600 & 549339\\
\hline
HD01\_VD35 & 55 to 64 years & With a disability & Congressional District 34 & 141 & 119 & 0.0195857 & 0.0232066 & 607586\\
\hline
HD01\_VD20 & 35 to 54 years & With a disability & Congressional District 09 & 179 & 114 & 0.0190103 & 0.0298495 & 599675\\
\hline
HD01\_VD05 & 18 to 34 years & With a disability & Congressional District 46 & 177 & 104 & 0.0189907 & 0.0323207 & 547637\\
\hline
HD01\_VD36 & 55 to 64 years & No disability & Congressional District 05 & 126 & 114 & 0.0189736 & 0.0209708 & 600835\\
\hline
HD01\_VD35 & 55 to 64 years & With a disability & Congressional District 33 & 145 & 108 & 0.0188835 & 0.0253529 & 571927\\
\hline
HD01\_VD06 & 18 to 34 years & No disability & Congressional District 36 & 140 & 115 & 0.0187065 & 0.0227731 & 614761\\
\hline
HD01\_VD21 & 35 to 54 years & No disability & Congressional District 40 & 112 & 98 & 0.0186398 & 0.0213026 & 525757\\
\hline
HD01\_VD20 & 35 to 54 years & With a disability & Congressional District 10 & 167 & 103 & 0.0183552 & 0.0297604 & 561149\\
\hline
HD01\_VD35 & 55 to 64 years & With a disability & Congressional District 26 & 122 & 103 & 0.0176623 & 0.0209204 & 583164\\
\hline
HD01\_VD50 & 65+ years & With a disability & Congressional District 40 & 128 & 89 & 0.0169280 & 0.0243458 & 525757\\
\hline
HD01\_VD51 & 65+ years & No disability & Congressional District 21 & 130 & 100 & 0.0166870 & 0.0216931 & 599270\\
\hline
HD01\_VD35 & 55 to 64 years & With a disability & Congressional District 38 & 115 & 91 & 0.0163139 & 0.0206165 & 557806\\
\hline
HD01\_VD51 & 65+ years & No disability & Congressional District 17 & 75 & 90 & 0.0162453 & 0.0135377 & 554007\\
\hline
HD01\_VD06 & 18 to 34 years & No disability & Congressional District 24 & 127 & 97 & 0.0160864 & 0.0210616 & 602994\\
\hline
HD01\_VD06 & 18 to 34 years & No disability & Congressional District 35 & 105 & 86 & 0.0157078 & 0.0191781 & 547499\\
\hline
HD01\_VD21 & 35 to 54 years & No disability & Congressional District 22 & 148 & 91 & 0.0152108 & 0.0247385 & 598258\\
\hline
HD01\_VD36 & 55 to 64 years & No disability & Congressional District 17 & 96 & 83 & 0.0149818 & 0.0173283 & 554007\\
\hline
HD01\_VD21 & 35 to 54 years & No disability & Congressional District 42 & 94 & 85 & 0.0149153 & 0.0164945 & 569886\\
\hline
HD01\_VD06 & 18 to 34 years & No disability & Congressional District 32 & 110 & 80 & 0.0145630 & 0.0200241 & 549339\\
\hline
HD01\_VD51 & 65+ years & No disability & Congressional District 23 & 86 & 72 & 0.0143816 & 0.0171780 & 500641\\
\hline
HD01\_VD21 & 35 to 54 years & No disability & Congressional District 14 & 123 & 81 & 0.0141805 & 0.0215334 & 571205\\
\hline
HD01\_VD06 & 18 to 34 years & No disability & Congressional District 39 & 93 & 78 & 0.0140587 & 0.0167623 & 554818\\
\hline
HD01\_VD05 & 18 to 34 years & With a disability & Congressional District 21 & 150 & 83 & 0.0138502 & 0.0250305 & 599270\\
\hline
HD01\_VD06 & 18 to 34 years & No disability & Congressional District 17 & 123 & 75 & 0.0135377 & 0.0222019 & 554007\\
\hline
HD01\_VD21 & 35 to 54 years & No disability & Congressional District 38 & 172 & 75 & 0.0134455 & 0.0308351 & 557806\\
\hline
HD01\_VD35 & 55 to 64 years & With a disability & Congressional District 20 & 142 & 79 & 0.0130934 & 0.0235350 & 603357\\
\hline
HD01\_VD36 & 55 to 64 years & No disability & Congressional District 26 & 112 & 70 & 0.0120035 & 0.0192056 & 583164\\
\hline
HD01\_VD21 & 35 to 54 years & No disability & Congressional District 09 & 115 & 69 & 0.0115062 & 0.0191771 & 599675\\
\hline
HD01\_VD20 & 35 to 54 years & With a disability & Congressional District 25 & 106 & 65 & 0.0114046 & 0.0185983 & 569944\\
\hline
HD01\_VD20 & 35 to 54 years & With a disability & Congressional District 19 & 77 & 64 & 0.0108633 & 0.0130699 & 589142\\
\hline
HD01\_VD06 & 18 to 34 years & No disability & Congressional District 05 & 75 & 64 & 0.0106518 & 0.0124826 & 600835\\
\hline
HD01\_VD05 & 18 to 34 years & With a disability & Congressional District 45 & 90 & 54 & 0.0103533 & 0.0172555 & 521573\\
\hline
HD01\_VD51 & 65+ years & No disability & Congressional District 12 & 100 & 60 & 0.0103106 & 0.0171843 & 581927\\
\hline
HD01\_VD36 & 55 to 64 years & No disability & Congressional District 32 & 92 & 56 & 0.0101941 & 0.0167474 & 549339\\
\hline
HD01\_VD21 & 35 to 54 years & No disability & Congressional District 15 & 97 & 57 & 0.0099645 & 0.0169572 & 572028\\
\hline
HD01\_VD05 & 18 to 34 years & With a disability & Congressional District 23 & 83 & 49 & 0.0097875 & 0.0165787 & 500641\\
\hline
HD01\_VD35 & 55 to 64 years & With a disability & Congressional District 30 & 89 & 53 & 0.0095687 & 0.0160682 & 553889\\
\hline
HD01\_VD06 & 18 to 34 years & No disability & Congressional District 19 & 93 & 55 & 0.0093356 & 0.0157857 & 589142\\
\hline
HD01\_VD21 & 35 to 54 years & No disability & Congressional District 21 & 86 & 55 & 0.0091778 & 0.0143508 & 599270\\
\hline
HD01\_VD05 & 18 to 34 years & With a disability & Congressional District 50 & 73 & 50 & 0.0091742 & 0.0133944 & 545004\\
\hline
HD01\_VD06 & 18 to 34 years & No disability & Congressional District 44 & 75 & 52 & 0.0091616 & 0.0132139 & 567584\\
\hline
HD01\_VD20 & 35 to 54 years & With a disability & Congressional District 40 & 79 & 48 & 0.0091297 & 0.0150260 & 525757\\
\hline
HD01\_VD05 & 18 to 34 years & With a disability & Congressional District 34 & 69 & 55 & 0.0090522 & 0.0113564 & 607586\\
\hline
HD01\_VD05 & 18 to 34 years & With a disability & Congressional District 38 & 82 & 49 & 0.0087844 & 0.0147005 & 557806\\
\hline
HD01\_VD20 & 35 to 54 years & With a disability & Congressional District 32 & 79 & 48 & 0.0087378 & 0.0143809 & 549339\\
\hline
HD01\_VD06 & 18 to 34 years & No disability & Congressional District 18 & 80 & 48 & 0.0087185 & 0.0145309 & 550551\\
\hline
HD01\_VD20 & 35 to 54 years & With a disability & Congressional District 04 & 84 & 51 & 0.0085895 & 0.0141473 & 593751\\
\hline
HD01\_VD05 & 18 to 34 years & With a disability & Congressional District 42 & 82 & 48 & 0.0084227 & 0.0143888 & 569886\\
\hline
HD01\_VD35 & 55 to 64 years & With a disability & Congressional District 35 & 77 & 46 & 0.0084018 & 0.0140640 & 547499\\
\hline
HD01\_VD05 & 18 to 34 years & With a disability & Congressional District 10 & 77 & 46 & 0.0081975 & 0.0137218 & 561149\\
\hline
HD01\_VD20 & 35 to 54 years & With a disability & Congressional District 39 & 73 & 45 & 0.0081108 & 0.0131575 & 554818\\
\hline
HD01\_VD05 & 18 to 34 years & With a disability & Congressional District 05 & 81 & 47 & 0.0078224 & 0.0134812 & 600835\\
\hline
HD01\_VD05 & 18 to 34 years & With a disability & Congressional District 16 & 64 & 38 & 0.0075114 & 0.0126508 & 505896\\
\hline
HD01\_VD06 & 18 to 34 years & No disability & Congressional District 10 & 70 & 41 & 0.0073064 & 0.0124744 & 561149\\
\hline
HD01\_VD35 & 55 to 64 years & With a disability & Congressional District 45 & 90 & 38 & 0.0072857 & 0.0172555 & 521573\\
\hline
HD01\_VD20 & 35 to 54 years & With a disability & Congressional District 47 & 68 & 41 & 0.0070026 & 0.0116141 & 585496\\
\hline
HD01\_VD36 & 55 to 64 years & No disability & Congressional District 24 & 56 & 42 & 0.0069652 & 0.0092870 & 602994\\
\hline
HD01\_VD35 & 55 to 64 years & With a disability & Congressional District 52 & 62 & 39 & 0.0067951 & 0.0108025 & 573939\\
\hline
HD01\_VD35 & 55 to 64 years & With a disability & Congressional District 05 & 65 & 40 & 0.0066574 & 0.0108183 & 600835\\
\hline
HD01\_VD20 & 35 to 54 years & With a disability & Congressional District 38 & 59 & 35 & 0.0062746 & 0.0105772 & 557806\\
\hline
HD01\_VD20 & 35 to 54 years & With a disability & Congressional District 11 & 55 & 33 & 0.0059993 & 0.0099988 & 550065\\
\hline
HD01\_VD20 & 35 to 54 years & With a disability & Congressional District 35 & 53 & 32 & 0.0058448 & 0.0096804 & 547499\\
\hline
HD01\_VD20 & 35 to 54 years & With a disability & Congressional District 29 & 50 & 31 & 0.0058389 & 0.0094175 & 530926\\
\hline
HD01\_VD05 & 18 to 34 years & With a disability & Congressional District 31 & 66 & 29 & 0.0055281 & 0.0125811 & 524597\\
\hline
HD01\_VD06 & 18 to 34 years & No disability & Congressional District 15 & 47 & 29 & 0.0050697 & 0.0082164 & 572028\\
\hline
HD01\_VD35 & 55 to 64 years & With a disability & Congressional District 10 & 42 & 26 & 0.0046334 & 0.0074846 & 561149\\
\hline
HD01\_VD05 & 18 to 34 years & With a disability & Congressional District 35 & 54 & 24 & 0.0043836 & 0.0098630 & 547499\\
\hline
HD01\_VD50 & 65+ years & With a disability & Congressional District 39 & 39 & 24 & 0.0043257 & 0.0070293 & 554818\\
\hline
HD01\_VD20 & 35 to 54 years & With a disability & Congressional District 20 & 42 & 24 & 0.0039777 & 0.0069611 & 603357\\
\hline
HD01\_VD35 & 55 to 64 years & With a disability & Congressional District 27 & 27 & 16 & 0.0029950 & 0.0050541 & 534217\\
\hline
HD01\_VD06 & 18 to 34 years & No disability & Congressional District 30 & 37 & 16 & 0.0028887 & 0.0066800 & 553889\\
\hline
HD01\_VD36 & 55 to 64 years & No disability & Congressional District 12 & 26 & 15 & 0.0025776 & 0.0044679 & 581927\\
\hline
HD01\_VD20 & 35 to 54 years & With a disability & Congressional District 37 & 29 & 13 & 0.0023913 & 0.0053345 & 543633\\
\hline
HD01\_VD05 & 18 to 34 years & With a disability & Congressional District 51 & 25 & 11 & 0.0019511 & 0.0044342 & 563796\\
\hline
HD01\_VD35 & 55 to 64 years & With a disability & Congressional District 21 & 23 & 10 & 0.0016687 & 0.0038380 & 599270\\
\hline
HD01\_VD06 & 18 to 34 years & No disability & Congressional District 20 & 210 & 0 & 0.0000000 & 0.0348053 & 603357\\
\hline
HD01\_VD06 & 18 to 34 years & No disability & Congressional District 12 & 210 & 0 & 0.0000000 & 0.0360870 & 581927\\
\hline
HD01\_VD06 & 18 to 34 years & No disability & Congressional District 25 & 210 & 0 & 0.0000000 & 0.0368457 & 569944\\
\hline
HD01\_VD06 & 18 to 34 years & No disability & Congressional District 29 & 210 & 0 & 0.0000000 & 0.0395535 & 530926\\
\hline
HD01\_VD06 & 18 to 34 years & No disability & Congressional District 40 & 210 & 0 & 0.0000000 & 0.0399424 & 525757\\
\hline
HD01\_VD36 & 55 to 64 years & No disability & Congressional District 15 & 210 & 0 & 0.0000000 & 0.0367115 & 572028\\
\hline
HD01\_VD05 & 18 to 34 years & With a disability & Congressional District 20 & 210 & 0 & 0.0000000 & 0.0348053 & 603357\\
\hline
HD01\_VD05 & 18 to 34 years & With a disability & Congressional District 09 & 210 & 0 & 0.0000000 & 0.0350190 & 599675\\
\hline
HD01\_VD05 & 18 to 34 years & With a disability & Congressional District 22 & 210 & 0 & 0.0000000 & 0.0351019 & 598258\\
\hline
HD01\_VD05 & 18 to 34 years & With a disability & Congressional District 04 & 210 & 0 & 0.0000000 & 0.0353684 & 593751\\
\hline
HD01\_VD05 & 18 to 34 years & With a disability & Congressional District 08 & 210 & 0 & 0.0000000 & 0.0356038 & 589824\\
\hline
HD01\_VD05 & 18 to 34 years & With a disability & Congressional District 19 & 210 & 0 & 0.0000000 & 0.0356451 & 589142\\
\hline
HD01\_VD05 & 18 to 34 years & With a disability & Congressional District 47 & 210 & 0 & 0.0000000 & 0.0358670 & 585496\\
\hline
HD01\_VD05 & 18 to 34 years & With a disability & Congressional District 26 & 210 & 0 & 0.0000000 & 0.0360105 & 583164\\
\hline
HD01\_VD05 & 18 to 34 years & With a disability & Congressional District 12 & 210 & 0 & 0.0000000 & 0.0360870 & 581927\\
\hline
HD01\_VD05 & 18 to 34 years & With a disability & Congressional District 13 & 210 & 0 & 0.0000000 & 0.0364803 & 575653\\
\hline
HD01\_VD05 & 18 to 34 years & With a disability & Congressional District 41 & 210 & 0 & 0.0000000 & 0.0365106 & 575176\\
\hline
HD01\_VD05 & 18 to 34 years & With a disability & Congressional District 52 & 210 & 0 & 0.0000000 & 0.0365893 & 573939\\
\hline
HD01\_VD05 & 18 to 34 years & With a disability & Congressional District 15 & 210 & 0 & 0.0000000 & 0.0367115 & 572028\\
\hline
HD01\_VD05 & 18 to 34 years & With a disability & Congressional District 33 & 210 & 0 & 0.0000000 & 0.0367180 & 571927\\
\hline
HD01\_VD05 & 18 to 34 years & With a disability & Congressional District 14 & 210 & 0 & 0.0000000 & 0.0367644 & 571205\\
\hline
HD01\_VD05 & 18 to 34 years & With a disability & Congressional District 25 & 210 & 0 & 0.0000000 & 0.0368457 & 569944\\
\hline
HD01\_VD05 & 18 to 34 years & With a disability & Congressional District 06 & 210 & 0 & 0.0000000 & 0.0372108 & 564352\\
\hline
HD01\_VD05 & 18 to 34 years & With a disability & Congressional District 48 & 210 & 0 & 0.0000000 & 0.0373966 & 561548\\
\hline
HD01\_VD05 & 18 to 34 years & With a disability & Congressional District 39 & 210 & 0 & 0.0000000 & 0.0378502 & 554818\\
\hline
HD01\_VD05 & 18 to 34 years & With a disability & Congressional District 17 & 210 & 0 & 0.0000000 & 0.0379057 & 554007\\
\hline
HD01\_VD05 & 18 to 34 years & With a disability & Congressional District 30 & 210 & 0 & 0.0000000 & 0.0379137 & 553889\\
\hline
HD01\_VD05 & 18 to 34 years & With a disability & Congressional District 43 & 210 & 0 & 0.0000000 & 0.0380849 & 551399\\
\hline
HD01\_VD05 & 18 to 34 years & With a disability & Congressional District 18 & 210 & 0 & 0.0000000 & 0.0381436 & 550551\\
\hline
HD01\_VD05 & 18 to 34 years & With a disability & Congressional District 11 & 210 & 0 & 0.0000000 & 0.0381773 & 550065\\
\hline
HD01\_VD05 & 18 to 34 years & With a disability & Congressional District 32 & 210 & 0 & 0.0000000 & 0.0382278 & 549339\\
\hline
HD01\_VD05 & 18 to 34 years & With a disability & Congressional District 37 & 210 & 0 & 0.0000000 & 0.0386290 & 543633\\
\hline
HD01\_VD05 & 18 to 34 years & With a disability & Congressional District 27 & 210 & 0 & 0.0000000 & 0.0393099 & 534217\\
\hline
HD01\_VD05 & 18 to 34 years & With a disability & Congressional District 29 & 210 & 0 & 0.0000000 & 0.0395535 & 530926\\
\hline
HD01\_VD05 & 18 to 34 years & With a disability & Congressional District 03 & 210 & 0 & 0.0000000 & 0.0397605 & 528162\\
\hline
HD01\_VD05 & 18 to 34 years & With a disability & Congressional District 40 & 210 & 0 & 0.0000000 & 0.0399424 & 525757\\
\hline
HD01\_VD05 & 18 to 34 years & With a disability & Congressional District 07 & 210 & 0 & 0.0000000 & 0.0404271 & 519454\\
\hline
HD01\_VD05 & 18 to 34 years & With a disability & Congressional District 49 & 210 & 0 & 0.0000000 & 0.0408853 & 513632\\
\hline
HD01\_VD20 & 35 to 54 years & With a disability & Congressional District 02 & 210 & 0 & 0.0000000 & 0.0316418 & 663679\\
\hline
HD01\_VD20 & 35 to 54 years & With a disability & Congressional District 12 & 210 & 0 & 0.0000000 & 0.0360870 & 581927\\
\hline
HD01\_VD20 & 35 to 54 years & With a disability & Congressional District 13 & 210 & 0 & 0.0000000 & 0.0364803 & 575653\\
\hline
HD01\_VD20 & 35 to 54 years & With a disability & Congressional District 15 & 210 & 0 & 0.0000000 & 0.0367115 & 572028\\
\hline
HD01\_VD20 & 35 to 54 years & With a disability & Congressional District 33 & 210 & 0 & 0.0000000 & 0.0367180 & 571927\\
\hline
HD01\_VD20 & 35 to 54 years & With a disability & Congressional District 14 & 210 & 0 & 0.0000000 & 0.0367644 & 571205\\
\hline
HD01\_VD20 & 35 to 54 years & With a disability & Congressional District 44 & 210 & 0 & 0.0000000 & 0.0369989 & 567584\\
\hline
HD01\_VD20 & 35 to 54 years & With a disability & Congressional District 48 & 210 & 0 & 0.0000000 & 0.0373966 & 561548\\
\hline
HD01\_VD20 & 35 to 54 years & With a disability & Congressional District 17 & 210 & 0 & 0.0000000 & 0.0379057 & 554007\\
\hline
HD01\_VD20 & 35 to 54 years & With a disability & Congressional District 30 & 210 & 0 & 0.0000000 & 0.0379137 & 553889\\
\hline
HD01\_VD20 & 35 to 54 years & With a disability & Congressional District 18 & 210 & 0 & 0.0000000 & 0.0381436 & 550551\\
\hline
HD01\_VD20 & 35 to 54 years & With a disability & Congressional District 46 & 210 & 0 & 0.0000000 & 0.0383466 & 547637\\
\hline
HD01\_VD20 & 35 to 54 years & With a disability & Congressional District 27 & 210 & 0 & 0.0000000 & 0.0393099 & 534217\\
\hline
HD01\_VD20 & 35 to 54 years & With a disability & Congressional District 45 & 210 & 0 & 0.0000000 & 0.0402628 & 521573\\
\hline
HD01\_VD20 & 35 to 54 years & With a disability & Congressional District 28 & 210 & 0 & 0.0000000 & 0.0448453 & 468276\\
\hline
HD01\_VD35 & 55 to 64 years & With a disability & Congressional District 09 & 210 & 0 & 0.0000000 & 0.0350190 & 599675\\
\hline
HD01\_VD35 & 55 to 64 years & With a disability & Congressional District 19 & 210 & 0 & 0.0000000 & 0.0356451 & 589142\\
\hline
HD01\_VD35 & 55 to 64 years & With a disability & Congressional District 14 & 210 & 0 & 0.0000000 & 0.0367644 & 571205\\
\hline
HD01\_VD35 & 55 to 64 years & With a disability & Congressional District 17 & 210 & 0 & 0.0000000 & 0.0379057 & 554007\\
\hline
HD01\_VD35 & 55 to 64 years & With a disability & Congressional District 49 & 210 & 0 & 0.0000000 & 0.0408853 & 513632\\
\hline
\end{tabular}
\end{table}


```r
library(readxl)
library(kableExtra)
library(ggplot2)
library(reshape2)
library(sp)
library(gghighlight)

income <- read_excel("Data.xlsx", sheet = "B21007")
income <- as.data.frame(income)

income.m <- melt(income, id = c("Age", "Disability", "Location", "Percent Affected", "Error"))


dodge=position_dodge(width=0)
p1 <- ggplot(income.m, aes(x=Location, y=income.m$`Percent Affected`, color=Age, shape=Disability)) +
  geom_point(alpha=0.9, position=dodge) + ylab("Percent of District Affected") + coord_flip()  + ggtitle("All Data")  #+ geom_errorbar(position=dodge, aes(ymin=Population-income.m$`Margin of Error`, ymax=Population+income.m$`Margin of Error`), width=.1)
  


# subset data and create new object based on column query

str(income.m$Disability)
```

```
##  chr [1:1696] "No disability" "No disability" "No disability" ...
```

```r
income.dis <- income.m[income.m$Disability == "With a disability" ,]

p2 <- ggplot(income.dis, aes(x=Location, y=income.dis$`Percent Affected`, color=Age)) +
  geom_point(alpha=0.9, position=dodge) + ylab("Percent of District Affected") + coord_flip() + ggtitle("Disabled Veterans Below Poverty Line")


str(income.m$Age)
```

```
##  chr [1:1696] "65+ years" "65+ years" "35 to 54 years" ...
```

```r
income.old <- income.m[income.m$Age == "65+ years" ,]

p3 <- ggplot(income.old, aes(x=Location, y=income.old$`Percent Affected`)) +
  geom_bar(stat= "identity", fill="mediumorchid1") + ylab("Percent of District Affected") + coord_flip() + ggtitle("Senior Veterans Below Poverty Line")

str(income.m$Location)
```

```
##  chr [1:1696] "Congressional District 36" "Congressional District 04" ...
```

```r
income.here <- income.m[income.m$Location == "Congressional District 41" ,]

p4 <- ggplot(income.here, aes(x=Age, y=income.here$`Percent Affected`, fill=Disability)) +
  geom_bar(stat="identity") + ylab("Percent of District Affected")  + ggtitle("District 41") 

p1
```

![](vet-data_files/figure-latex/unnamed-chunk-10-1.pdf)<!-- --> 

```r
p2
```

![](vet-data_files/figure-latex/unnamed-chunk-10-2.pdf)<!-- --> 

```r
p3
```

![](vet-data_files/figure-latex/unnamed-chunk-10-3.pdf)<!-- --> 

```r
p4
```

![](vet-data_files/figure-latex/unnamed-chunk-10-4.pdf)<!-- --> 

```r
pdf("demos.pdf")
# set plot so it is 2x2 in one plot canvas
par(mfrow=c(2,2)) 
p1
p2
p3
p4
dev.off()
```

```
## pdf 
##   2
```
--A trend that it may be increasing. Show a figure of vet population over time. 

# VA Capacity

Capacity -  VA health care locations compared to demographics, kinds of care/specialties
  outpaitent services
  number of patients
  Mental Health
  Community based clinics are based on Health Centers
  Trajectory of capacity
  Ecancer
  telemedicine
  
# VA Clinic Quality

This is VA data for VA clinics in California

![](vet-data_files/figure-latex/unnamed-chunk-11-1.pdf)<!-- --> 

Quality - Complaint data, Ratings, Long beach data from Gerry, Takano may be able to get data for 
  $600 per patient, cost of patient is actualy \$200



This VA data focuses on quality rating of Medical Centers in California. 

![](vet-data_files/figure-latex/unnamed-chunk-12-1.pdf)<!-- --> 

```
## pdf 
##   2
```

As a reference for these data points:

\begin{table}[H]
\centering
\begin{tabular}{l|l}
\hline
Codes & Condition\\
\hline
F1 & Colorectal Cancer Screening\\
\hline
F2 & Flu Vaccinations for Adults Ages 18-64\\
\hline
F3 & Medical Assistance with Smoking and Tobacco Use Cessation - Advising Smokers To Quit\\
\hline
F4 & Medical Assistance with Smoking and Tobacco Use Cessation - Discussing Cessation Medications\\
\hline
F5 & Medical Assistance with Smoking and Tobacco Use Cessation - Discussing Cessation Strategies\\
\hline
F6 & Non-Recommended PSA-Based Screening in Older Men\\
\hline
F7 & Breast Cancer Screening\\
\hline
F8 & Cervical Cancer Screening\\
\hline
F9 & Controlling High Blood Pressure\\
\hline
F10 & Persistence of Beta-Blocker Treatment after a Heart Attack\\
\hline
F11 & Statin Therapy for Patients With Cardiovascular Disease Received Statin Therapy - 21-75 years (Male)\\
\hline
F12 & Statin Therapy for Patients With Cardiovascular Disease Received Statin Therapy - 40-75 years (Female)\\
\hline
F13 & Statin Therapy for Patients With Cardiovascular Disease Received Statin Therapy - Total\\
\hline
F14 & Comprehensive Diabetes Care - Blood Pressure Control (<140/90)\\
\hline
F15 & Comprehensive Diabetes Care - Eye Exams\\
\hline
F16 & Comprehensive Diabetes Care - HbA1c Control (<7\% for a selected population)\\
\hline
F17 & Comprehensive Diabetes Care - HbA1c Testing\\
\hline
F18 & Comprehensive Diabetes Care - Medical Attention for Nephropathy\\
\hline
F19 & Comprehensive Diabetes Care - Poor HbA1c Control\\
\hline
F20 & Statin Therapy for Patients With Diabetes Received Statin Therapy\\
\hline
F21 & Antidepressant Medication Management - Effective Acute Phase Treatment\\
\hline
F22 & Antidepressant Medication Management - Effective Continuation Phase Treatment\\
\hline
\end{tabular}
\end{table}

# VA Accessiblity 

Waittimes, transportation/drive times, San bernadino,


# Conclusion:
Students here for UCR for veterans. Major bus route, 91, 215.


Ideal outcome: Winning contract for 5 CBOCs, over building one here. RFP
Hybrid, community owned, Va owned. CBOCs are lucrative

# To Do:
Learn more about Arcadia location that just opened- Nepalitono, june, shift, their case for clinic - provides access to those without a car. 

Email Ignacio about getting VA rank and branch info for va clinics so we can look at the needs of each branch and what will be needed here as far as services go. 

