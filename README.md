Repozitář obsahuje to samé, co bylo dříve ve vm na wedosu.

Klient stahuje jary a ověřuje kontrolní součet stejným způsobem, jen to bere z našeho github repozitáře

Repozitář obsahuje default a trial verzi validátoru ( standardně bere default )

Není kolem toho žádná automatika → pokud se rozhodneme aktualizovat validátor, je potřeba ručně vydat novou release s novým validátorem a kontrolním součtem ( md5 ) a změnit url

Z klienta to obstarává třída cz.alis.keong.ssljdr.sip.zaf.ClientZafValidator
