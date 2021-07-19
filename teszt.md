# Teszt

Név: Sisák Ádám 

## Kérdések:

1. Mit értünk egy `commit` alatt, mit tartalmaz?
A commit egy módosított vagy egy nem kovetett fájlról készít snapshotot, és a helyi repóba biztonságosan elmenti azt. Módosított fájl esetén tartalmazza a módosításokat. Commit-olás esetén
mindig meg kell adni egy message-t, hogy miről szól a módosítás.  
1. Mi a különbség a `fetch` es `pull` git parancsok között?
Mindkettő a remote repóból leszedi a legfrissebb commitokat a snapshotokról, de a pull automatikusan merge-li is ezeket.
1. Mi a három állapota file-oknak git szempontjából, milyen parancsokkal mozgatjuk ezek között?
untacked, tracked, staged
git add segítségével tudjuk nyomon követni az untracked fájlokat, git add segítségével stageli is,
git rm segítségével tudjuk visszaléptetni az állapotokat.
1. Hogyan jutunk egy másolathoz egy repóról?
git clone parancs segítségével, vagy pedig Forkoljuk az adott repót.
1. Mi történik, ha valaki más is módosította a file-t amin dolgozunk és mit tudunk tenni ilyenkor?
Commit-olás esetén konfliktus keletkezik, amiről értesít a Git, ilyenkor Merge-lni kell az adott fájlt, lehetőségünk van eldönteni, hogy melyik változtatást szeretnénk megtartani.
1. Mi az a `HEAD` és mi a jelentősége?
A HEAD alatt a branchen a legfrissebb, aktuálisan feltöltött commitot, snapshotot értjük.
1. Mi a célja a branch-elésnek?
Ha egy adott projekten dolgozunk, nem a fő branchen fogunk fejleszteni, mert oda a végleges termék kerül. A patchekhez, fejlesztésekhez, feature-khöz hozunk létre különálló brancheket,
majd a végleges változat commitját át mergel-jük a fő branchbe.
1. Hogyan lehet összehasonlítani file-ok változásait, mire tudjuk még ezt a kimenetet használni?
Git diff paranccsal.
Repók közötti külnönbséget is mutatja.
1. Hogy lehet megnézni egy repo történetét, milyen eszközeink vannak ebben való keresésre?
Git log paranccsal.
1. Melyik git parancsot használnád, hogy megtudd milyen állapotban van épp a repo?
Git status paranccsal.
