# aurora-homebrew
Ein paar kleine Erklärungen: 
-in "homebrew_core.index" sind alle xml dateien aufgeführt, wenn du eine neue addest, müsste die da noch hinzugefügt werden.
-Als "source" in den xmls sollten wir immer die gleiche bezeichnung nutzen, dann werden all unsere items auch in der gleichen Kategorie im Compendium aufgelistet.
-in "statblocks.xml" habe ich angefangen Statblocks für z.B. Kreaturen, die mit einem Item oder Spell beschworen werden, oder in die man sich verwandeln kann, aufzulisten. Diese statblocks kann man dann einfach in ein Item integrieren, wie ich es bei z.B. bei dem Snow Wolfs Cowl gemacht habe. Die Statblocks habe ich der Einfachheit halber einfach in die Shop-Kategorie "Mounts" gepackt
Ganz wichtig: wenn du neue Items hinzufügst und die anderen die auch gleich bekommen können sollen, muss die Versionsnummer in den XML Dateien erhöht werden, weil Aurora sonst nicht checkt, dass die Datei auch neu ist und lokal aktualisiert werden muss