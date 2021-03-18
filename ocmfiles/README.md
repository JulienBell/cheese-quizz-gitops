# Creation Application dans ACM

Créer un namespace githubcom-julienbell-cheese-quizz-gitops-ns

Création channel:
 githubcom-julienbell-cheese-quizz-gitops-ns/githubcom-julienbell-cheese-quizz-gitops

    oc apply -f ocmfiles/cheese-quizz-channel.yml


Créer via interface avec user kubeadmin le projet uat
Prendre :
- https://github.com/JulienBell/cheese-quizz-gitops
- ./gitops/overlays/uat
- Local server