Lien pour le site déployé par verse : tp-dev-sec-ops.vercel.app

les analytics ont été mises en plae via l'installation du package, l'import du module ainsi que le placement dee la balise <Analytics/> dans le fichier layout.tsx, conformément à la documentation vercel.

le projet à été importé dans sneak, et le rapport HTML à été généré via cette commande : snyk test --json | snyk-to-html -o rapport.html,
il est disponible dans les fichiers sur ce repository github sous le nom de rapport.html