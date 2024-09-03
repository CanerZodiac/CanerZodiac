import random

Futbolcu = ["Lionel Messi", "Cristiano Ronaldo", "Neymar Jr.", "Kylian Mbappe", "Kevin De Bruyne",
            "Mohamed Salah", "Robert Lewandowski", "Virgil van Dijk", "Karim Benzema", "Luka Modric",
            "Erling Haaland", "Harry Kane", "Sergio Ramos", "Eden Hazard", "Sadio Mane",
            "Paul Pogba", "Toni Kroos", "Gerard Pique", "Zlatan Ibrahimovic", "Gareth Bale",
            "Luis Suarez", "Antoine Griezmann", "Pierre-Emerick Aubameyang", "Romelu Lukaku",
            "Philippe Coutinho", "David de Gea", "Manuel Neuer", "Raheem Sterling", "Thibaut Courtois",
            "Edinson Cavani", "Jadon Sancho", "Thiago Silva", "Marco Reus", "Joshua Kimmich",
            "Marcelo Vieira", "Andres Iniesta", "Sergio Busquets", "Angel Di Maria", "Alisson Becker",
            "Jan Oblak", "Frenkie de Jong", "Matthijs de Ligt", "Paulo Dybala", "Joao Felix",
            "Bernardo Silva", "Vinicius Jr.", "Son Heung-min", "Leonardo Bonucci", "Gianluigi Donnarumma",
            "Trent Alexander-Arnold", "Andy Robertson", "Hakim Ziyech", "Christian Pulisic",
            "Bruno Fernandes", "Marquinhos", "Rodri", "Federico Valverde", "Kai Havertz",
            "Ciro Immobile", "Lautaro Martinez", "Raphael Varane", "Jordi Alba", "Fabinho",
            "Riyad Mahrez", "Jorginho", "Kalidou Koulibaly", "Alexis Sanchez", "Ederson Moraes",
            "Aymeric Laporte", "Lucas Hernandez", "Kingsley Coman", "Marco Verratti", "Achraf Hakimi",
            "Serge Gnabry", "Leon Goretzka", "Dani Carvajal", "Mats Hummels", "Gerard Moreno",
            "Dusan Tadic", "Memphis Depay", "N'Golo Kante", "Ivan Rakitic", "Diego Godin",
            "Cesar Azpilicueta", "Miralem Pjanic", "Fernandinho", "Mason Mount", "Reece James",
            "Phil Foden", "Mason Greenwood", "Bukayo Saka", "Jack Grealish", "Declan Rice",
            "Jordan Henderson", "James Maddison", "Dominic Calvert-Lewin", "Marcus Rashford",
            "Jude Bellingham", "Thiago Alcantara", "Pedro Neto", "Ruben Neves", "Wilfried Zaha",
            "John Stones", "Xavi Hernandez", "Iker Casillas", "Francesco Totti", "Andrea Pirlo",
            "Frank Lampard", "Steven Gerrard", "Wayne Rooney", "David Beckham", "Fernando Torres",
            "Carles Puyol", "Thierry Henry", "Zinedine Zidane", "Ronaldinho", "Rivaldo", "Cafu",
            "Roberto Carlos", "Alessandro Del Piero", "Pavel Nedved", "Luis Figo", "Ronaldo Nazario",
            "Andriy Shevchenko", "Didier Drogba", "Samuel Eto'o", "Michael Ballack", "Gianluigi Buffon",
            "Fabio Cannavaro", "Paolo Maldini", "Franco Baresi", "Lilian Thuram", "George Weah",
            "Kaka", "Clarence Seedorf", "Ruud van Nistelrooy", "Ryan Giggs", "Paul Scholes",
            "Gary Neville", "Peter Schmeichel", "Nemanja Vidic", "Rio Ferdinand", "John Terry",
            "Ashley Cole", "Marc Overmars", "Patrick Vieira", "Robert Pires", "Emmanuel Petit",
            "David Trezeguet", "Hernan Crespo", "Juan Roman Riquelme", "Gabriel Batistuta",
            "Javier Zanetti", "Esteban Cambiasso", "Miroslav Klose", "Lukas Podolski",
            "Bastian Schweinsteiger", "Philipp Lahm", "Mesut Ozil", "Mario Gotze", "Thomas Muller",
            "Arjen Robben", "Wesley Sneijder", "Robin van Persie", "Dirk Kuyt", "Jaap Stam",
            "Edgar Davids", "Ruud Gullit", "Frank Rijkaard", "Marco van Basten", "Roberto Baggio",
            "Paolo Rossi", "Giuseppe Meazza", "Silvio Piola", "Gianni Rivera", "Dino Zoff",
            "Gaetano Scirea", "Alessandro Nesta", "Daniele De Rossi", "David Luiz", "Oscar",
            "Willian", "Robinho", "Fred", "Julio Cesar", "Dida", "Zico", "Socrates", "Arthur Zico",
            "Romario", "Bebeto", "Carlos Alberto", "Zizinho", "Hugo Sanchez", "Clint Dempsey",
            "Landon Donovan", "Brian McBride", "Brad Friedel", "Tim Howard", "David Villa",
            "Raul Gonzalez", "Fernando Hierro", "Jose Antonio Camacho", "Michel Salgado",
            "Santiago Canizares", "Joaquin Sanchez", "Sergio Busquets", "Gerard Pique",
            "Cesc Fabregas", "David Silva", "Xabi Alonso", "Juan Mata", "Andres Iniesta"]

print("Futbolcu Bilme Oyununa Hoşgeldin, Başlamak için Enter'a bas", end=" ")
print("R tuşuna basıp çıkabilirsiniz")
kullanici_giris = input().lower()

if kullanici_giris == "r":
    print("Oyundan Çıkılmıştır")
    exit()

print("Haydi Başlayalım")

rastgele_futbolcu = random.choice(Futbolcu)  # Rastgele bir futbolcu seçiyoruz
print(f"Futbolcunun ismi: {rastgele_futbolcu}")

son_harf = rastgele_futbolcu[-1].lower()  # Futbolcunun son harfini alıyoruz
print(f"Yeni futbolcunun bu harfle başlaması gerekiyor: {son_harf.upper()}")

while True:
    kullanici_futbolcu = input("Yeni futbolcu ismini gir: ").strip()

    if kullanici_futbolcu.lower() == "r":
        print("Oyundan Çıkılmıştır")
        break

    # Kullanıcı, verilen son harfle başlayan bir futbolcu ismi girdi mi?
    if kullanici_futbolcu[0].lower() == son_harf and kullanici_futbolcu in Futbolcu:
        print("Doğru! Oyun devam ediyor.")
        son_harf = kullanici_futbolcu[-1].lower()  # Yeni futbolcunun son harfini alıyoruz
        print(f"Şimdi bu harfle yeni bir futbolcu ismi girmeniz gerekiyor: {son_harf.upper()}")
    else:
        print("Yanlış giriş veya futbolcu listede yok. Oyun bitti!")
        break
