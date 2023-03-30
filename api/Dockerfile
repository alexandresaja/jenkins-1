# Image de base python
FROM python

# Création du répertoire /app
RUN mkdir /app

# Définition du répertoire de travail
WORKDIR /app

# Exposition du port 5000
EXPOSE 5000

# Copie des éléments du répertoire courrant dans le répertoire de travail
COPY . .

# Initialisation des prérequis avec pip install
RUN pip install -r requirements.txt


CMD ["flask","run","--host=0.0.0.0"]