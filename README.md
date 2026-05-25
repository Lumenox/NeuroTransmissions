# NeuroTransmissions
Transmissions à partir d'une DB locale

to_do
voir avec les autres quelles cellules ajouter
mode synthèse?


pour créer de nouvelles cellules à remplir:
{name:'psychomot', label:'Psychomotricien', type:'textarea', section:'nursing'},

Pour personnaliser les unités:
1/Dans le tableau FIELDS, chaque champ peut recevoir une propriété hideInUnits
{name:'devenir', label:'Devenir / Transfert', type:'select', section:'devenir',
  options:["En cours d'évaluation","Transférable UNV","Non transférable UNV",...],
  hideInUnits:['UNV'] },  

2/renderPatients()
