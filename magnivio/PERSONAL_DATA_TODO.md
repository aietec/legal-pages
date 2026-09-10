# Personal data to complete

No real personal data is included. Replace every marker before commercial publication. Visible HTML intentionally displays “Information to complete” (or equivalent).

| Marker | Files | Expected information | Consequence if missing |
|---|---|---|---|
| `{{NOM_LEGAL_A_COMPLETER}}` | all `legal*.html`, all `privacy*.html` | Full legal identity of publisher/controller | Publisher/controller cannot be identified |
| `{{NOM_COMMERCIAL_A_COMPLETER}}` | all `legal*.html` | Trading name, if applicable | Commercial identity incomplete |
| `{{STATUT_JURIDIQUE_A_COMPLETER}}` | all `legal*.html` | Legal form/status | Mandatory publisher information incomplete |
| `{{ADRESSE_PROFESSIONNELLE_A_COMPLETER}}` | all `legal*.html` | Publisher’s professional address | Mandatory contact information incomplete; do not substitute GitHub’s address |
| `{{SIREN_OU_SIRET_A_COMPLETER}}` | all `legal*.html` | French SIREN or SIRET, if applicable | Registration information incomplete |
| `{{IMMATRICULATION_RNE_A_COMPLETER}}` | all `legal*.html` | RNE registration details, if applicable | Registration notice incomplete |
| `{{EMAIL_ASSISTANCE_A_COMPLETER}}` | all `support*.html`, `terms*.html`, `legal*.html` | Monitored support email address | Users cannot contact support; `mailto:` is unusable |
| `{{EMAIL_CONFIDENTIALITE_A_COMPLETER}}` | all `privacy*.html`, `support*.html`, `legal*.html` | Monitored privacy email address | Data-subject requests cannot be submitted; `mailto:` is unusable |
| `{{DIRECTEUR_PUBLICATION_A_COMPLETER}}` | all `legal*.html` | Publication director/responsible person | Mandatory publication information incomplete |

After replacement, run a global search for `{{` and revalidate every `mailto:` link. Obtain legal review before publication.
