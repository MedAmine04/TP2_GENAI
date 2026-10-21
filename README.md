Modèles Génératifs avec PyTorch
📖 Description
Ce projet est un notebook Jupyter complet explorant les principaux paradigmes des modèles génératifs en Deep Learning, implémentés avec PyTorch. Il sert de guide pratique et pédagogique pour comprendre, implémenter et visualiser le fonctionnement des autoencodeurs, des autoencodeurs variationnels (VAE), des réseaux antagonistes génératifs (GAN) et des modèles de diffusion (Diffusion Models) sur le jeu de données MNIST.

📚 Contenu du Notebook
Le notebook est structuré en plusieurs parties progressives :
Introduction aux modèles génératifs : Distinction entre modèles discriminatifs (
P
(
y
∣
x
)
P(y∣x)) et génératifs (
P
(
x
)
P(x)).
Autoencodeur (AE) :
Architecture Encodeur-Décodeur.
Fonction de perte de reconstruction (MSE).
Visualisation des reconstructions et de l'espace latent.
Autoencodeur Variationnel (VAE) :
Principe de la distribution latente 
q
(
z
∣
x
)
=
N
(
μ
,
σ
2
)
q(z∣x)=N(μ,σ 
2
 ).
Astuce de reparamétrisation (Reparameterization trick).
Fonction de perte combinée (Reconstruction + Divergence KL).
Visualisation de l'espace latent continu et génération de nouvelles images.
Réseaux Antagonistes Génératifs (GAN) :
Principe du jeu à somme nulle entre le Générateur et le Discriminateur.
Architecture des deux réseaux (Linear + LeakyReLU/Sigmoid).
Boucle d'entraînement alternée et fonctions de perte (BCEWithLogitsLoss).
Génération d'images après l'entraînement.
Modèles de Diffusion (Diffusion Models) :
Principe de débruitage progressif.
Processus forward (ajout de bruit avec un calendrier cosinus).
Processus reverse (prédiction du bruit par un réseau U-Net simplifié).
Architecture du U-Net (Encodeur, Middle, Décodeur avec connexions résiduelles/skip connections).
Boucle d'entraînement pour prédire le bruit ajouté.
