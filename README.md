# Drum machine and Schroeder Reverb
Acest proiect consta in construirea unui patch in max pentru un Drum machine si pentru un efect reverb ( Schroeder reverberator).

## (Instalare)
Se descarca patchul de proiect si se va deschide cu programul Max 7 sau 8. Apoi parametrii vor fi modificati in functie de dorintele utilizatorului ( beat-ul pe care doreste sa il faca, tonul sunetelor, efectul de reverberatie).

## (Utilizare)
Patchul pentru efectul de reverb are doua knob-uri simple care vor face modificari parametrice pentru a modifica tipul de reverberatii pe care le obtinem pentru orice sunet folosit.
Patchul pentru drum machine se foloseste de o matrice in care pot fi adaugate/ sterse elemente, viteza de redare poate sa fie modificata din parametrul BPM, numarul de coloane ce pot sa fie folosite este modificat cu ajutorul parametrului steps, iar pentru a diversifica beat-ul se va folosi parametrul de shuffle pentru a sari peste anumite note in functie de valoarea utilizata. Sunetele au parametrii ce modifica tonalitatea prin modificarea frecventelor si a timpilor de decay.

## (Istoric)

(13.05) Patchul pentru reverb a fost facut si urcat pe github

(3.06) Patchul pentru drum machine a fost facut si urcat pe github

(11.06) Patchul pentru proiectul final a facut si urcat pe github

## (Link-uri)
    comment:Snare
    url:https://www.youtube.com/watch?v=5VBmqk9v4Kk&t=389s
    licence:
  - comment:Kick
    url:https://www.youtube.com/watch?v=86EpMhBCNbo&t=453s
    licence:
  - comment:Step sequencer
    url:https://www.youtube.com/watch?v=hYc2a1ONTck&list=PLD45EDA6F67827497&index=2
    licence:
  - comment:Schroeder Reverb
    url:https://www.youtube.com/watch?v=SJiOXhbF810
    licence:
  - comment:Schroeder Reverb
    url:https://www.youtube.com/watch?v=F_FhvxT5mLA
    licence:    

# Dezvoltarea proiectului

Pentru început:

1. Creează-ți cont pe Github
2. Download și install [Github Desktop](https://desktop.github.com/)
3. Citește [acest ghid](https://charlesmartin.com.au/blog/2020/08/09/student-project-repository) și ține la îndemână [Markdown Cheat Sheet](https://www.markdownguide.org/cheat-sheet).

Apoi, procesul este următorul (inspirat de [aici](https://cs.anu.edu.au/courses/comp1720/deliverables/05-major-project/#submission-process)):

1. *fork* al acestui template către propriul tău cont de Github

![](assets/fork.gif)

_(dacă preferi cumva ca repo-ul să nu fie vizibil de către public, îl poți seta ca Private din Settings - "Change visibility". Atunci trebuie să mă adaugi drept colaborator, ca eu să am acces.)_

2. *clone* al repo-ului din Github Desktop pentru a-l downloada local

![](assets/clone.gif)

3. *commit* și *push* pe măsură ce lucrezi la proiect. Ultima versiune push-ată pe server înainte de deadline va conta pentru evaluare.

![](assets/commit.gif)

## Elemente obligatorii

1. Acest readme completat. Titlu, descriere, mod de utilizare, istoric, link-uri utile.

   Poți include și imagini și chiar [gif-uri animate](https://www.screentogif.com/), sau link-uri către materiale audio/video.
   
   Vezi [aici](https://charlesmartin.com.au/blog/2020/08/09/student-project-repository) mai multe sugestii.

2. [Declarația de originalitate](statement-of-originality.yml) completată. Tot ce nu este inclus acolo va fi considerat 100% contribuție proprie.

    *(formatul este adaptat de [aici](https://gitlab.cecs.anu.edu.au/comp1720/2018/comp1720-2018-major-project/-/blob/master/statement-of-originality.yml). Da, este un pic ironic să refolosim un doc [de altundeva](https://cs.anu.edu.au/courses/comp1720/resources/faq/#how-do-i-fill-out-my-statement-of-originality), dar menționăm sursa deci nu este plagiat!)*

3. Proiectul în sine. Tot codul trebuie să fie prezent, proiectul trebuie să poată rula conform instrucțiunilor din readme. Dacă e nevoie de asset-uri mari (sunete, video etc), [folosește Git LFS](https://git-lfs.github.com/) sau include link de download în instrucțiunile de instalare.

