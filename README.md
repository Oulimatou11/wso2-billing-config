# WSO2 Micro Integrator – Billing Integration

## Déscription
WSO2 Micro Integrator  est utilisé comme une couche d'integration pour exposer, sécuriser et orchestrer les services de facturation.
WSO2 MI joue le role d'API Gateway les applications clientes et les microservices backend.

## APIs Exposées
- Service Billing Legacy SOAP: `http://localhost:8290/api/legacy/billing`
- Microservices Billing Service RESTful: `http://localhost:8290/api/v2/billing`

## Automatisation
- WSO2 a également été utilisé pour planifier le scrapping de l'API REST BRVM qui concernent des données boursiéres
