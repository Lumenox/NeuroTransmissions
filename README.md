# NeuroTransmissions
Transmissions à partir d'une DB locale

to_do
-voir avec les autres quelles cellules ajouter
-mode synthèse?
-onglet recherche

pour créer de nouvelles cellules à remplir:
{name:'psychomot', label:'Psychomotricien', type:'textarea', section:'nursing'},

Pour personnaliser les unités:
Dans le tableau FIELDS, chaque champ peut recevoir une propriété hideInUnits
{name:'devenir', label:'Devenir / Transfert', type:'select', section:'devenir',
  options:["En cours d'évaluation","Transférable UNV","Non transférable UNV",...],
  hideInUnits:['UNV'] },  


Pour changer les unités:
-les définir dans const UNITS
-les changer dans renderPatientForm 
