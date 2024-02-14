# Bazele GIT și GitHub

git tutorial 2024

## GIT este un sistem distribuit.

Ce-nseamnă asta? Înseamnă că în momentul în care te apuci de un proiect nou, poți ține toate fișierele din acel proiect într-un container de GIT, numit în engleză Repository (sau repo). Toate fișierele site-ului tău pot sta într-un astfel de repo, și unul din avantaje este că dacă repo-ul este creat de un serviciu extern cum este GitHub, este disponibil de oriunde din lume, de pe orice calculator. Asta înseamnă că dacă schimbi calculatorul pe care muncești și ți-ai făcut repo-ul public (sau te loghezi cu userul și parola de GitHub pe alt calculator), ai acces de oriunde la proiectul tău. Practic, asta permite și lucrul în echipă – poți da acces mai multor oameni la repo și cu toții vor putea să-l acceseze – sau dacă e public, îl poate accesa oricine îi știe adresa web. Și în plus, există și posibilitatea ca toți oamenii implicați în proiect să lucreze în ritmul lor la proiect, nu în același timp neapărat.


## GIT este un sistem de control al surselor cu versionare. 

Asta-nseamnă că poți stoca pe perioadă nedeterminată și în același loc toate versiunile prin care a trecut site-ul tău și fiecare fișier în parte, ca să te poți întoarce oricând la o variantă anterioară. Implicit, dacă folosești GitHub, asta înseamnă că ai backup aproape infinit al proiectului în cloud și dacă ți se strică la un moment dat calculatorul (sau proiectul), îl poți recupera sau poți accesa și deploya o variantă mai veche a lui care funcționa bine.


## GIT este un sistem colaborativ. 

Cum ziceam și la început, indiferent dacă în echipă sunteți 2 oameni sau 200, cu toții pot conviețui și contribui la același proiect fără prea mari bătăi de cap, datorită felului cum e gândit sistemul colaborativ. Vom vorbi mai în detaliu despre asta în viitor, însă ce trebuie să reții acum e că poți să-ți imaginezi GIT ca un copac special în care fiecare ramură este o clonă perfectă a ramurii din care se trage inițial. Apoi, fiecare ramură evoluează și se îmbunătățește. La un moment dat, ramura aia se întoarce în trunchi și asta face ca trunchiul să primească toate îmbunătățirile și noutățile cu care a venit acea ramură. Din punctul ăla încolo, îmbunătățirile astea se reflectă în toate noile ramuri care răsar ulterior. E un arbore care evoluează sub ochii tăi, pe măsură ce echipa lucrează la el să-l perfecționeze. Și din metafora asta a copacului vine și terminologia de „branch”, adică ramură. Din ramura sau branch-ul „main” (adică cel principal, trunchiul cum ar veni) poți crea oricând o ramură care clonează acest „main”, o poți împodobi cu modificări minunate, și mai apoi o poți contopi (sau merge-ui) înapoi în „main” ca să beneficieze toată lumea din echipă (și vizitatorii site-ului) de minunățiile făcute de tine.
