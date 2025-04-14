# Indicados ao Oscar
Utilização do MongoDB no desenvolvimento de conceitos iniciais referentes á banco de dados.

Nos arquivos **JSON**, contém a base de indicados ao Oscar em formato SQL para treinar comandos CRUD.

*Abaixo, as atividades a serem feitas com suas respectivas repostas.*

Obs.: tabela resgistros (referenciada nas atividades) = tabela indicados

------

✅ Atualize os registros da tabela com os dados do Oscar 2025

------

1. Qual o total de registros na tabela indicados?

R: 11020

Q: 
```db.registros.count()```

------

2. Qual o número de indicações por categoria agrupadas por categoria?

R: <details> <summary>Veja a resposata completa expandindo aqui.</summary>
```
{_id: 'DIRECTING', total_indicacoes: 469}
{_id: 'FILM EDITING', total_indicacoes: 450}
{_id: 'ACTRESS IN A SUPPORTING ROLE', total_indicacoes: 440}
{_id: 'ACTOR IN A SUPPORTING ROLE', total_indicacoes: 440}
{_id: 'DOCUMENTARY (Short Subject)', total_indicacoes: 378}
{_id: 'BEST PICTURE', total_indicacoes: 371}
{_id: 'DOCUMENTARY (Feature)', total_indicacoes: 345}
{_id: 'CINEMATOGRAPHY', total_indicacoes: 338}
{_id: 'FOREIGN LANGUAGE FILM', total indicações: 315}
{_id: 'ART DIRECTION', total_indicacoes: 307}
{_id: 'COSTUME DESIGN', total_indicacoes: 295}
{_id: 'MUSIC (Original Score)', total_indicacoes: 270}
{_id: 'SOUND', total_indicacoes: 245}
{_id: 'ACTRESS IN A LEADING ROLE', total_indicacoes: 240}
{_id: 'ACTOR IN A LEADING ROLE', total_indicacoes: 240}
{_id: 'ACTRESS', total_indicacoes: 236}
{_id: 'MUSIC (Original Song)', total_indicacoes: 235}
{_id: 'ACTOR', total_indicacoes: 232}
{_id: 'SHORT FILM (Live Action)', total_indicacoes: 226}
{_id: 'MUSIC (Song)', total_indicacoes: 215}
{_id: 'SHORT FILM (Animated)', total_indicacoes: 215}
{_id: 'SOUND RECORDING', total_indicacoes: 195}
{_id: 'SHORT SUBJECT (Cartoon)', total_indicacoes: 169}
{_id: 'CINEMATOGRAPHY (Black-and-White)', total_indicacoes: 161}
{_id: 'WRITING (Original Screenplay)', total_indicacoes: 160}
{_id: 'VISUAL EFFECTS', total_indicacoes: 155}
{_id: 'MUSIC (Music Score of a Dramatic or Comedy Picture)', total_indicacoes: 148}
{_id: 'ART DIRECTION (Black-and-White)', total_indicacoes: 138}
{_id: 'CINEMATOGRAPHY (Color)', total_indicacoes: 135}
{_id: 'HONORARY AWARD', total_indicacoes: 133}
{_id: 'MUSIC (Scoring of a Musical Picture)', total_indicacoes: 127}
{_id: 'WRITING (Screenplay Written Directly for the Screen)', total_indicacoes: 120}
{_id: 'ART DIRECTION (Color)', total_indicacoes: 112}
{_id: 'WRITING (Adapted Screenplay)', total_indicacoes: 110}
{_id: 'WRITING (Screenplay)', total_indicacoes: 104}
{_id: 'OUTSTANDING PRODUCTION', total_indicacoes: 102}
{_id: 'ANIMATED FEATURE FILM', total_indicacoes: 99}
{_id: 'WRITING (Screenplay--based on material from another medium)', total_indicacoes: 95}
{_id: 'SPECIAL EFFECTS', total_indicacoes: 93}
{_id: 'SHORT SUBJECT (One-reel)', total_indicacoes: 90}
{_id: 'BEST MOTION PICTURE', total_indicacoes: 90}
{_id: 'MAKEUP', total_indicacoes: 87}
{_id: 'SOUND EDITING', total_indicacoes: 86}
{_id: 'SOUND MIXING', total_indicacoes: 85}
{_id: 'SHORT SUBJECT (Two-reel)', total_indicacoes: 81}
{_id: 'COSTUME DESIGN (Black-and-White)', total_indicacoes: 77}
{_id: 'COSTUME DESIGN (Color)', total_indicacoes: 77}
{_id: 'SHORT SUBJECT (Live Action)', total_indicacoes: 68}
{_id: 'WRITING (Screenplay Based on Material from Another Medium)', total_indicacoes: 65}
{_id: 'MUSIC (Scoring)', total_indicacoes: 64}
{_id: 'WRITING (Story and Screenplay--written directly for the screen)', total_indicacoes: 60}
{_id: 'PRODUCTION DESIGN', total_indicacoes: 60}
{_id: 'SPECIAL AWARD', total_indicacoes: 56}
{_id: 'WRITING (Screenplay Based on Material Previously Produced or Published)', total_indicacoes: 55}
{_id: 'WRITING (Original Story)', total_indicacoes: 52}
{_id: 'WRITING (Motion Picture Story)', total_indicacoes: 50}
{_id: 'SOUND EFFECTS EDITING', total_indicacoes: 47}
{_id: 'MAKEUP AND HAIRSTYLING', total_indicacoes: 46}
{_id: 'IRVING G. THALBERG MEMORIAL AWARD', total_indicacoes: 45}
{_id: 'JEAN HERSHOLT HUMANITARIAN AWARD', total_indicacoes: 44}
{_id: 'MUSIC (Original Dramatic Score)', total_indicacoes: 41}
{_id: 'WRITING (Story and Screenplay)', total_indicacoes: 35}
{_id: 'ASSISTANT DIRECTOR', total_indicacoes: 35}
{_id: 'MUSIC (Scoring of Music--adaptation or treatment)', total_indicacoes: 30}
{_id: 'OUTSTANDING MOTION PICTURE', total_indicacoes: 30}
{_id: 'DOCUMENTARY', total_indicacoes: 25}
{_id: 'MUSIC (Song--Original for the Picture)', total_indicacoes: 25}
{_id: 'INTERNATIONAL FEATURE FILM', total_indicacoes: 25}
{_id: 'WRITING (Original Motion Picture Story)', total_indicacoes: 25}
{_id: 'DANCE DIRECTION', total_indicacoes: 21}
{_id: 'MUSIC (Original Musical or Comedy Score)', total_indicacoes: 20}
{_id: 'MUSIC (Music Score--substantially original)', total_indicacoes: 20}
{_id: 'MUSIC (Music Score of a Dramatic Picture)', total_indicacoes: 20}
{_id: 'WRITING (Story and Screenplay--based on factual material or material not previously published or produced)', total_indicacoes: 20}
{_id: 'WRITING (Adaptation)', total_indicacoes: 17}
{_id: 'SPECIAL VISUAL EFFECTS', total_indicacoes: 16}
{_id: 'SHORT SUBJECT (Comedy)', total_indicacoes: 13}
{_id: 'SHORT SUBJECT (Novelty)', total_indicacoes: 12}
{_id: 'WRITING', total_indicacoes: 11}
{_id: 'DOCUMENTARY SHORT FILM', total_indicacoes: 10}
{_id: 'MUSIC (Score of a Musical Picture--original or adaptation)', total_indicacoes: 10}
{_id: 'Best Documentary Short Film', total_indicacoes: 10}
{_id: 'SOUND EFFECTS', total_indicacoes: 10}
{_id: 'DOCUMENTARY FEATURE FILM', total_indicacoes: 10}
{_id: 'Best Supporting Actor', total_indicacoes: 10}
{_id: 'WRITING (Screenplay Written Directly for the Screen--based on factual material or on story material not previously published or produced)', total_indicacoes: 10}
{_id: 'MUSIC (Original Music Score)', total_indicacoes: 10}
{_id: 'MUSIC (Original Score--for a motion picture [not a musical])', total_indicacoes: 10}
{_id: 'Best Costume Design', total_indicacoes: 10}
{_id: 'Best Picture', total_indicacoes: 10}
{_id: 'WRITING (Screenplay Adapted from Other Material)', total_indicacoes: 10}
{_id: 'Best International Feature Film', total_indicacoes: 10}
{_id: 'SHORT SUBJECT (Animated)', total_indicacoes: 9}
{_id: 'SPECIAL ACHIEVEMENT AWARD (Visual Effects)', total_indicacoes: 9}
{_id: 'MUSIC (Scoring: Original Song Score and Adaptation -or- Scoring: Adaptation)', total_indicacoes: 9}
{_id: 'MUSIC (Scoring: Adaptation and Original Song Score)', total_indicacoes: 8}
{_id: 'MUSIC (Original Song Score)', total_indicacoes: 8}
{_id: 'OUTSTANDING PICTURE', total_indicacoes: 8}
{_id: 'MUSIC (Original Song Score and Its Adaptation -or- Adaptation Score)', total_indicacoes: 6}
{_id: 'SHORT SUBJECT (Color)', total_indicacoes: 6}
{_id: 'MUSIC (Original Song Score and Its Adaptation or Adaptation Score)', total_indicacoes: 6}
{_id: 'Best Actor', total_indicacoes: 5}
{_id: 'Best Sound', total_indicacoes: 5}
{_id: 'Best Original Score', total_indicacoes: 5}
{_id: 'Best Animated Short Film', total_indicacoes: 5}
{_id: 'WRITING (Screenplay--Original)', total_indicacoes: 5}
{_id: 'WRITING (Screenplay--Original)', total_indicacoes: 5}
{_id: 'Best Film Editing', total_indicacoes: 5}
{_id: 'Best Supporting Actress', total_indicacoes: 5}
{_id: 'HONORARY FOREIGN LANGUAGE FILM AWARD', total_indicacoes: 5}
{_id: 'WRITING (Story and Screenplay--based on material not previously published or produced)', total_indicacoes: 5}
{_id: 'Best Adapted Screenplay', total_indicacoes: 5}
{_id: 'Best Visual Effects', total_indicacoes: 5}
{_id: 'Best Makeup and Hairstyling', total_indicacoes: 5}
{_id: 'Best Cinematography', total_indicacoes: 5}
{_id: 'Best Live Action Short Film', total_indicacoes: 5}
{_id: 'Best Original Song', total_indicacoes: 5}
{_id: 'Best Original Screenplay', total_indicacoes: 5}
{_id: 'WRITING (Screenplay--Adapted)', total_indicacoes: 5}
{_id: 'Best Documentary Feature', total_indicacoes: 5}
{_id: 'Best Directing', total_indicacoes: 5}
{_id: 'SPECIAL ACHIEVEMENT AWARD (Sound Effects Editing)', total_indicacoes: 4}
{_id: 'UNIQUE AND ARTISTIC PICTURE', total_indicacoes: 3}
{_id: 'MUSIC (Adaptation Score)', total_indicacoes: 3}
{_id: 'WRITING (Title Writing)', total_indicacoes: 3}
{_id: 'ENGINEERING EFFECTS', total_indicacoes: 3}
{_id: 'DIRECTING (Dramatic Picture)', total_indicacoes: 3}
{_id: 'SHORT FILM (Dramatic Live Action)', total_indicacoes: 3}
{_id: 'SPECIAL ACHIEVEMENT AWARD', total_indicacoes: 3}
{_id: 'MUSIC (Original Song Score or Adaptation Score)', total_indicacoes: 3}
{_id: 'DIRECTING (Comedy Picture)', total_indicacoes: 2}
{_id: 'SPECIAL FOREIGN LANGUAGE FILM AWARD', total_indicacoes: 2}
{_id: 'SPECIAL ACHIEVEMENT AWARD (Sound Effects)', total_indicacoes: 1}
{_id: 'SPECIAL ACHIEVEMENT AWARD (Sound Effects)', total_indicacoes: 1}
{_id: null, total_indicacoes: 1}
{_id: 'GORDON E. SAWYER AWARD', total_indicacoes: 1}
{_id: 'AWARD OF COMMENDATION', total_indicacoes: 1}

```
</details>

Q: 
```
db.registros.aggregate([
  {
    $group: {
      _id: "$categoria",  
      total_indicacoes: { $sum: 1 }  
    }
  },
  {
    $sort: { total_indicacoes: -1 } 
  }
]);
```

------

3. Quantas vezes Natalie Portman foi indicada ao Oscar?

R: 3 vezes

Q:  ``` db.registros.countDocuments({ nome_do_indicado: "Natalie Portman" }) ```

------

4. Quantos Oscars Natalie Portman ganhou?

R: 1 vez

Q: ``` db.indicados.countDocuments({ nome_do_indicado: "Natalie Portman", vencedor: "true" }) ```


------

5. Quantas vezes Viola Davis foi indicada ao Oscar?

R: 4 vezes

Q:  ``` db.registros.countDocuments({ nome_do_indicado: "Viola Davis" }) ```

------

6. Quantos Oscars Viola Davis ganhou?

R: 1 vez

Q: ``` db.indicados.countDocuments({ nome_do_indicado: "Viola Davis", vencedor: "true" }) ```

------

7. Amy Adams já ganhou algum Oscar?

R: Amy Adams não ganhou nenhum Oscar

Q: ``` db.indicados.count({ nome_do_indicado: "Amy Adams", vencedor: true }) ```

------

8. Quais os atores/atrizes que foram indicados mais de uma vez?

R:<details> <summary>Veja a resposata completa expandindo aqui.</summary>
```
{ _id: 'Sally Field', indicacoes: 3 }
{ _id: 'Christoph Waltz', indicacoes: 2 }
{ _id: 'Daniel Day-Lewis', indicacoes: 5 }
{ _id: 'Melinda Dillon', indicacoes: 2 }
{ _id: 'Jack Lemmon', indicacoes: 8 }
{ _id: 'Sal Mineo', indicacoes: 2 }
{ _id: 'Michael Shannon', indicacoes: 2 }
{ _id: 'Goldie Hawn', indicacoes: 2 }
{ _id: 'Al Pacino', indicacoes: 9 }
{ _id: 'Tom Wilkinson', indicacoes: 2 }
{ _id: 'Jon Voight', indicacoes: 4 }
{ _id: 'Agnes Moorehead', indicacoes: 4 }
{ _id: 'Richard Farnsworth', indicacoes: 2 }
{ _id: 'Wallace Beery', indicacoes: 2 }
{ _id: 'Joan Cusack', indicacoes: 2 }
{ _id: 'Dustin Hoffman', indicacoes: 7 }
{ _id: 'Thelma Ritter', indicacoes: 6 }
{ _id: 'George C. Scott', indicacoes: 4 }
{ _id: 'Eddie Redmayne', indicacoes: 2 }
{ _id: 'Cher', indicacoes: 2 }
{ _id: 'Paul Muni', indicacoes: 6 }
{ _id: 'Leonardo DiCaprio', indicacoes: 6 }
{ _id: 'Renée Zellweger', indicacoes: 4 }
{ _id: 'Hilary Swank', indicacoes: 2 }
{ _id: 'Joan Allen', indicacoes: 3 }
{ _id: 'Norma Shearer', indicacoes: 6 }
{ _id: 'Claire Trevor', indicacoes: 3 }
{ _id: 'Angela Bassett', indicacoes: 2 }
{ _id: 'Gary Cooper', indicacoes: 5 }
{ _id: 'Michael Fassbender', indicacoes: 2 }
{ _id: 'Gloria Grahame', indicacoes: 2 }
{ _id: 'Fredric March', indicacoes: 5 }
{ _id: 'Luise Rainer', indicacoes: 2 }
{ _id: 'Juliette Binoche', indicacoes: 2 }
{ _id: 'Julie Walters', indicacoes: 2 }
{ _id: 'John Garfield', indicacoes: 2 }
{ _id: 'Alan Arkin', indicacoes: 4 }
{ _id: 'Burt Lancaster', indicacoes: 4 }
{ _id: 'Richard Dreyfuss', indicacoes: 2 }
{ _id: 'Jonah Hill', indicacoes: 2 }
{ _id: 'Jude Law', indicacoes: 2 }
{ _id: 'Marcello Mastroianni', indicacoes: 3 }
{ _id: 'Clifton Webb', indicacoes: 3 }
{ _id: "Peter O'Toole", indicacoes: 8 }
{ _id: 'Rosalind Russell', indicacoes: 4 }
{ _id: 'Amy Adams', indicacoes: 6 }
{ _id: 'Claudette Colbert', indicacoes: 3 }
{ _id: 'Gena Rowlands', indicacoes: 2 }
{ _id: 'Burgess Meredith', indicacoes: 2 }
{ _id: 'Walter Huston', indicacoes: 4 }
{ _id: 'Irene Dunne', indicacoes: 5 }
{ _id: 'Ben Kingsley', indicacoes: 4 }
{ _id: 'Rooney Mara', indicacoes: 2 }
{ _id: 'Timothée Chalamet', indicacoes: 2 }
{ _id: 'Frank Sinatra', indicacoes: 2 }
{ _id: 'Bette Midler', indicacoes: 2 }
{ _id: 'Nicolas Cage', indicacoes: 2 }
{ _id: 'Gary Oldman', indicacoes: 3 }
{ _id: 'Cynthia Erivo', indicacoes: 2 }
{ _id: 'Jennifer Jones', indicacoes: 5 }
{ _id: 'Johnny Depp', indicacoes: 3 }
{ _id: 'Penélope Cruz', indicacoes: 4 }
{ _id: 'Anne Baxter', indicacoes: 2 }
{ _id: 'Marie Dressler', indicacoes: 2 }
{ _id: 'Fay Bainter', indicacoes: 3 }
{ _id: 'Elsa Lanchester', indicacoes: 2 }
{ _id: 'Peter Finch', indicacoes: 2 }
{ _id: 'Natalie Wood', indicacoes: 3 }
{ _id: 'Monty Woolley', indicacoes: 2 }
{ _id: 'Marisa Tomei', indicacoes: 3 }
{ _id: 'Paul Scofield', indicacoes: 2 }
{ _id: 'Michelle Pfeiffer', indicacoes: 3 }
{ _id: 'James Cagney', indicacoes: 3 }
{ _id: 'Olivia de Havilland', indicacoes: 5 }
{ _id: 'Walter Matthau', indicacoes: 3 }
{ _id: 'Madeline Kahn', indicacoes: 2 }
{ _id: 'Mary McDonnell', indicacoes: 2 }
{ _id: 'Charles Bickford', indicacoes: 3 }
{ _id: 'Ellen Burstyn', indicacoes: 6 }
{ _id: 'Holly Hunter', indicacoes: 4 }
{ _id: 'Octavia Spencer', indicacoes: 3 }
{ _id: 'Jeremy Renner', indicacoes: 2 }
{ _id: 'Winona Ryder', indicacoes: 2 }
{ _id: 'Mercedes McCambridge', indicacoes: 2 }
{ _id: 'Karl Malden', indicacoes: 2 }
{ _id: 'Heath Ledger', indicacoes: 2 }
{ _id: 'Janet Gaynor', indicacoes: 2 }
{ _id: 'Colman Domingo', indicacoes: 2 }
{ _id: 'Edmund Gwenn', indicacoes: 2 }
{ _id: 'Bing Crosby', indicacoes: 3 }
{ _id: 'Alec Guinness', indicacoes: 4 }
{ _id: 'Alice Brady', indicacoes: 2 }
{ _id: 'Joaquin Phoenix', indicacoes: 4 }
{ _id: 'Gloria Swanson', indicacoes: 3 }
{ _id: 'Mickey Rooney', indicacoes: 4 }
{ _id: 'Clint Eastwood', indicacoes: 2 }
{ _id: 'Ryan Gosling', indicacoes: 3 }
{ _id: 'Marcia Gay Harden', indicacoes: 2 }
{ _id: 'Shelley Winters', indicacoes: 4 }
{ _id: 'Audrey Hepburn', indicacoes: 5 }
{ _id: 'Charlize Theron', indicacoes: 3 }
{ _id: 'Maximilian Schell', indicacoes: 3 }
{ _id: 'Henry Fonda', indicacoes: 2 }
{ _id: 'Maggie Smith', indicacoes: 6 }
{ _id: 'Ed Harris', indicacoes: 4 }
{ _id: 'Angelina Jolie', indicacoes: 2 }
{ _id: 'Samantha Morton', indicacoes: 2 }
{ _id: 'Anne Bancroft', indicacoes: 5 }
{ _id: 'Jessica Lange', indicacoes: 6 }
{ _id: 'Kathy Bates', indicacoes: 4 }
{ _id: 'Jane Fonda', indicacoes: 7 }
{ _id: 'Javier Bardem', indicacoes: 4 }
{ _id: 'Paul Newman', indicacoes: 9 }
{ _id: 'Roy Scheider', indicacoes: 2 }
{ _id: 'Jeff Bridges', indicacoes: 7 }
{ _id: 'Marsha Mason', indicacoes: 4 }
{ _id: 'Adrien Brody', indicacoes: 2 }
{ _id: 'Max von Sydow', indicacoes: 2 }
{ _id: 'Kenneth Branagh', indicacoes: 2 }
{ _id: 'James Dean', indicacoes: 2 }
{ _id: 'Bette Davis', indicacoes: 11 }
{ _id: 'Sissy Spacek', indicacoes: 6 }
{ _id: 'Peter Sellers', indicacoes: 2 }
{ _id: 'Shirley MacLaine', indicacoes: 5 }
{ _id: 'Vincent Gardenia', indicacoes: 2 }
{ _id: 'Maureen Stapleton', indicacoes: 4 }
{ _id: 'Tom Hanks', indicacoes: 6 }
{ _id: 'Dianne Wiest', indicacoes: 3 }
{ _id: 'Ruth Chatterton', indicacoes: 2 }
{ _id: 'Charles Laughton', indicacoes: 3 }
{ _id: 'Jamie Foxx', indicacoes: 2 }
{ _id: 'Emma Stone', indicacoes: 4 }
{ _id: 'Richard Burton', indicacoes: 7 }
{ _id: 'Joyce Redman', indicacoes: 2 }
{ _id: 'Akim Tamiroff', indicacoes: 2 }
{ _id: 'Bradley Cooper', indicacoes: 5 }
{ _id: 'Ian McKellen', indicacoes: 2 }
{ _id: 'Debra Winger', indicacoes: 3 }
{ _id: 'Ethel Barrymore', indicacoes: 4 }
{ _id: 'Robert Duvall', indicacoes: 7 }
{ _id: 'Benicio Del Toro', indicacoes: 2 }
{ _id: 'John Lithgow', indicacoes: 2 }
{ _id: 'Meryl Streep', indicacoes: 21 }
{ _id: 'Gale Sondergaard', indicacoes: 2 }
{ _id: 'Sidney Poitier', indicacoes: 2 }
{ _id: 'Bruce Dern', indicacoes: 2 }
{ _id: 'Frank Morgan', indicacoes: 2 }
{ _id: 'Dame May Whitty', indicacoes: 2 }
{ _id: 'Jill Clayburgh', indicacoes: 2 }
{ _id: 'Jack Palance', indicacoes: 3 }
{ _id: 'Laura Linney', indicacoes: 3 }
{ _id: 'Wendy Hiller', indicacoes: 3 }
{ _id: 'J. Carrol Naish', indicacoes: 2 }
{ _id: 'Judy Garland', indicacoes: 2 }
{ _id: 'Glenda Jackson', indicacoes: 4 }
{ _id: 'Helen Hayes', indicacoes: 2 }
{ _id: 'Matt Damon', indicacoes: 3 }
{ _id: 'Joan Fontaine', indicacoes: 3 }
{ _id: 'Anna Magnani', indicacoes: 2 }
{ _id: 'Albert Finney', indicacoes: 5 }
{ _id: 'Victor McLaglen', indicacoes: 2 }
{ _id: 'Jane Alexander', indicacoes: 4 }
{ _id: 'Will Smith', indicacoes: 3 }
{ _id: 'Catherine Keener', indicacoes: 2 }
{ _id: 'Thomas Mitchell', indicacoes: 2 }
{ _id: 'Sandra Bullock', indicacoes: 2 }
{ _id: 'Brenda Blethyn', indicacoes: 2 }
{ _id: 'Olivia Colman', indicacoes: 3 }
{ _id: 'Kirk Douglas', indicacoes: 3 }
{ _id: "Arthur O'Connell", indicacoes: 2 }
{ _id: 'Viggo Mortensen', indicacoes: 3 }
{ _id: 'Anne Hathaway', indicacoes: 2 }
{ _id: 'Jack Warden', indicacoes: 2 }
{ _id: 'Simone Signoret', indicacoes: 2 }
{ _id: 'Robin Williams', indicacoes: 4 }
{ _id: 'Whoopi Goldberg', indicacoes: 2 }
{ _id: 'Ann-Margret', indicacoes: 2 }
{ _id: 'Angela Lansbury', indicacoes: 3 }
{ _id: 'Richard Jenkins', indicacoes: 2 }
{ _id: 'Peter Ustinov', indicacoes: 3 }
{ _id: 'Diane Ladd', indicacoes: 3 }
{ _id: 'Geoffrey Rush', indicacoes: 4 }
{ _id: 'Nick Nolte', indicacoes: 3 }
{ _id: 'Maria Ouspenskaya', indicacoes: 2 }
{ _id: 'Faye Dunaway', indicacoes: 3 }
{ _id: 'Barbra Streisand', indicacoes: 2 }
{ _id: 'Clark Gable', indicacoes: 3 }
{ _id: 'Casey Affleck', indicacoes: 2 }
{ _id: 'Loretta Young', indicacoes: 2 }
{ _id: 'Geena Davis', indicacoes: 2 }
{ _id: 'Julianne Moore', indicacoes: 5 }
{ _id: 'Geraldine Page', indicacoes: 8 }
{ _id: 'Eleanor Parker', indicacoes: 3 }
{ _id: 'Helen Mirren', indicacoes: 4 }
{ _id: 'Russell Crowe', indicacoes: 3 }
{ _id: 'William Powell', indicacoes: 3 }
{ _id: 'Deborah Kerr', indicacoes: 6 }
{ _id: 'Nicole Kidman', indicacoes: 5 }
{ _id: 'Susan Sarandon', indicacoes: 5 }
{ _id: 'Adam Driver', indicacoes: 2 }
{ _id: 'Martin Landau', indicacoes: 3 }
{ _id: 'Tom Cruise', indicacoes: 3 }
{ _id: 'Paul Giamatti', indicacoes: 2 }
{ _id: 'Anthony Quinn', indicacoes: 4 }
{ _id: 'Anjelica Huston', indicacoes: 3 }
{ _id: 'Christian Bale', indicacoes: 4 }
{ _id: 'Celeste Holm', indicacoes: 3 }
{ _id: 'Melvyn Douglas', indicacoes: 3 }
{ _id: 'Gene Hackman', indicacoes: 5 }
{ _id: 'Naomi Watts', indicacoes: 2 }
{ _id: 'Beulah Bondi', indicacoes: 2 }
{ _id: 'John Travolta', indicacoes: 2 }
{ _id: 'John Hurt', indicacoes: 2 }
{ _id: 'Teresa Wright', indicacoes: 3 }
{ _id: 'Ethan Hawke', indicacoes: 2 }
{ _id: 'Marjorie Rambeau', indicacoes: 2 }
{ _id: 'Walter Pidgeon', indicacoes: 2 }
{ _id: 'Melissa McCarthy', indicacoes: 2 }
{ _id: 'José Ferrer', indicacoes: 3 }
{ _id: 'James Stewart', indicacoes: 5 }
{ _id: 'Lee Grant', indicacoes: 4 }
{ _id: 'Benedict Cumberbatch', indicacoes: 2 }
{ _id: 'Piper Laurie', indicacoes: 3 }
{ _id: 'Viola Davis', indicacoes: 4 }
{ _id: 'Reese Witherspoon', indicacoes: 2 }
{ _id: 'Warren Beatty', indicacoes: 4 }
{ _id: 'Keira Knightley', indicacoes: 2 }
{ _id: 'Basil Rathbone', indicacoes: 2 }
{ _id: 'Greer Garson', indicacoes: 7 }
{ _id: 'Humphrey Bogart', indicacoes: 3 }
{ _id: 'Robert De Niro', indicacoes: 8 }
{ _id: 'Arthur Kennedy', indicacoes: 5 }
{ _id: 'Ralph Fiennes', indicacoes: 3 }
{ _id: 'John Wayne', indicacoes: 2 }
{ _id: 'Diane Keaton', indicacoes: 4 }
{ _id: 'Edward Norton', indicacoes: 3 }
{ _id: 'Ingrid Bergman', indicacoes: 7 }
{ _id: 'William Hurt', indicacoes: 4 }
{ _id: 'Cecil Kellaway', indicacoes: 2 }
{ _id: 'Annette Bening', indicacoes: 5 }
{ _id: 'Claude Rains', indicacoes: 4 }
{ _id: 'Sophia Loren', indicacoes: 2 }
{ _id: 'Ralph Richardson', indicacoes: 2 }
{ _id: 'Walter Brennan', indicacoes: 4 }
{ _id: 'Robert Montgomery', indicacoes: 2 }
{ _id: 'Elizabeth Taylor', indicacoes: 5 }
{ _id: 'Ruth Gordon', indicacoes: 2 }
{ _id: 'Hugh Griffith', indicacoes: 2 }
{ _id: 'Laurence Olivier', indicacoes: 9 }
{ _id: 'Susan Hayward', indicacoes: 5 }
{ _id: 'Sigourney Weaver', indicacoes: 3 }
{ _id: 'Michelle Williams', indicacoes: 5 }
{ _id: 'Helen Hunt', indicacoes: 2 }
{ _id: 'Shirley Knight', indicacoes: 2 }
{ _id: 'Glenn Close', indicacoes: 8 }
{ _id: 'Djimon Hounsou', indicacoes: 2 }
{ _id: 'Mark Ruffalo', indicacoes: 4 }
{ _id: 'Morgan Freeman', indicacoes: 5 }
{ _id: 'Estelle Parsons', indicacoes: 2 }
{ _id: "Edmond O'Brien", indicacoes: 2 }
{ _id: 'Willem Dafoe', indicacoes: 4 }
{ _id: 'Billy Bob Thornton', indicacoes: 2 }
{ _id: 'Michael Caine', indicacoes: 6 }
{ _id: 'Miranda Richardson', indicacoes: 2 }
{ _id: 'Eileen Heckart', indicacoes: 2 }
{ _id: 'Woody Harrelson', indicacoes: 3 }
{ _id: 'Richard Harris', indicacoes: 2 }
{ _id: 'Emma Thompson', indicacoes: 4 }
{ _id: 'Julia Roberts', indicacoes: 4 }
{ _id: 'Anne Revere', indicacoes: 3 }
{ _id: 'James Whitmore', indicacoes: 2 }
{ _id: 'Jodie Foster', indicacoes: 5 }
{ _id: 'Janet McTeer', indicacoes: 2 }
{ _id: 'Jessica Chastain', indicacoes: 3 }
{ _id: 'Talia Shire', indicacoes: 2 }
{ _id: 'Gladys Cooper', indicacoes: 3 }
{ _id: 'Margot Robbie', indicacoes: 2 }
{ _id: 'Sally Hawkins', indicacoes: 2 }
{ _id: 'Jean Simmons', indicacoes: 2 }
{ _id: 'Mildred Dunnock', indicacoes: 2 }
{ _id: 'Laura Dern', indicacoes: 3 }
{ _id: 'Cate Blanchett', indicacoes: 8 }
{ _id: 'Judy Davis', indicacoes: 2 }
{ _id: 'Charles Durning', indicacoes: 2 }
{ _id: 'Sylvia Miles', indicacoes: 2 }
{ _id: 'Joe Pesci', indicacoes: 3 }
{ _id: 'Julie Christie', indicacoes: 4 }
{ _id: 'Brad Pitt', indicacoes: 4 }
{ _id: 'Eddie Albert', indicacoes: 2 }
{ _id: 'Charles Coburn', indicacoes: 3 }
{ _id: 'Ronald Colman', indicacoes: 3 }
{ _id: 'Jason Robards', indicacoes: 3 }
{ _id: 'Rex Harrison', indicacoes: 2 }
{ _id: 'Gig Young', indicacoes: 3 }
{ _id: 'Scarlett Johansson', indicacoes: 2 }
{ _id: 'Judi Dench', indicacoes: 8 }
{ _id: 'Colin Firth', indicacoes: 2 }
{ _id: 'Leslie Howard', indicacoes: 2 }
{ _id: 'James Woods', indicacoes: 2 }
{ _id: 'Jacki Weaver', indicacoes: 2 }
{ _id: 'Charles Boyer', indicacoes: 4 }
{ _id: 'Dame Edith Evans', indicacoes: 3 }
{ _id: 'Liza Minnelli', indicacoes: 2 }
{ _id: 'Jennifer Lawrence', indicacoes: 4 }
{ _id: 'Judd Hirsch', indicacoes: 2 }
{ _id: 'Kim Stanley', indicacoes: 2 }
{ _id: 'Saoirse Ronan', indicacoes: 4 }
{ _id: 'Christopher Walken', indicacoes: 2 }
{ _id: 'Jessica Tandy', indicacoes: 2 }
{ _id: 'Kevin Spacey', indicacoes: 2 }
{ _id: 'Spencer Tracy', indicacoes: 9 }
{ _id: 'Cary Grant', indicacoes: 2 }
{ _id: 'Dyan Cannon', indicacoes: 2 }
{ _id: 'George Arliss', indicacoes: 2 }
{ _id: 'Isabelle Adjani', indicacoes: 2 }
{ _id: 'Joanne Woodward', indicacoes: 4 }
{ _id: 'Mahershala Ali', indicacoes: 2 }
{ _id: 'Barbara Stanwyck', indicacoes: 4 }
{ _id: 'Joan Crawford', indicacoes: 3 }
{ _id: 'Peter Falk', indicacoes: 2 }
{ _id: 'Patricia Neal', indicacoes: 2 }
{ _id: 'Sean Penn', indicacoes: 5 }
{ _id: 'Marlon Brando', indicacoes: 8 }
{ _id: 'Rod Steiger', indicacoes: 3 }
{ _id: 'Jack Nicholson', indicacoes: 12 }
{ _id: 'Melissa Leo', indicacoes: 2 }
{ _id: 'Tom Courtenay', indicacoes: 2 }
{ _id: 'Frances McDormand', indicacoes: 6 }
{ _id: 'Gregory Peck', indicacoes: 5 }
{ _id: 'Greta Garbo', indicacoes: 3 }
{ _id: 'Montgomery Clift', indicacoes: 4 }
{ _id: 'Andrew Garfield', indicacoes: 2 }
{ _id: 'John Gielgud', indicacoes: 2 }
{ _id: 'Daniel Kaluuya', indicacoes: 2 }
{ _id: 'Tommy Lee Jones', indicacoes: 4 }
{ _id: 'John Malkovich', indicacoes: 2 }
{ _id: 'Vivien Leigh', indicacoes: 2 }
{ _id: 'George Clooney', indicacoes: 4 }
{ _id: 'Natalie Portman', indicacoes: 3 }
{ _id: 'Vanessa Redgrave', indicacoes: 6 }
{ _id: 'Sam Rockwell', indicacoes: 2 }
{ _id: 'Lee J. Cobb', indicacoes: 2 }
{ _id: 'Jane Wyman', indicacoes: 4 }
{ _id: 'Katharine Hepburn', indicacoes: 12 }
{ _id: 'Liv Ullmann', indicacoes: 2 }
{ _id: 'Marion Cotillard', indicacoes: 2 }
{ _id: 'Robert Downey Jr.', indicacoes: 3 }
{ _id: 'Julie Andrews', indicacoes: 3 }
{ _id: 'Helena Bonham Carter', indicacoes: 2 }
{ _id: 'Denzel Washington', indicacoes: 9 }
{ _id: 'Sylvester Stallone', indicacoes: 2 }
{ _id: 'James Mason', indicacoes: 3 }
{ _id: 'Philip Seymour Hoffman', indicacoes: 4 }
{ _id: 'Grace Kelly', indicacoes: 2 }
{ _id: 'Lynn Redgrave', indicacoes: 2 }
{ _id: 'Robert Donat', indicacoes: 2 }
{ _id: 'Emily Watson', indicacoes: 2 }
{ _id: 'Barry Fitzgerald', indicacoes: 2 }
{ _id: 'Christopher Plummer', indicacoes: 3 }
{ _id: 'Kate Winslet', indicacoes: 7 }
{ _id: 'J.K. Simmons', indicacoes: 2 }
{ _id: 'Leslie Caron', indicacoes: 2 }
{ _id: 'Carey Mulligan', indicacoes: 3 }
{ _id: 'Anthony Hopkins', indicacoes: 6 }
{ _id: 'Rachel Weisz', indicacoes: 2 }
{ _id: 'William Holden', indicacoes: 3 }
```
</details>

Q: 
```
db.registros.aggregate([
  { $match: { categoria: { $in: ["ACTOR", "ACTRESS", "Best Actress", "Best Actor","ACTRESS IN A SUPPORTING ROLE","ACTOR IN A SUPPORTING ROLE"] } } },
  { $group: { _id: "$nome_do_indicado", indicacoes: { $sum: 1 } } },
  { $match: { indicacoes: { $gt: 1 } } }
]); 
```

------

9. A série de filmes Toy Story ganhou Oscars em quais anos?

R: 2011 e 2019

Q:``` db.registros.find({ nome_do_filme: /Toy Story/, vencedor: "true" }, { ano_cerimonia: 1, _id: 0 }); ```

------

10. A partir de que ano que a categoria "Actress" deixa de existir?

R: 1977, sendo 1976 o último ano com a categoria "Actress" presente.

Q:``` db.registros.find({ categoria: "ACTRESS" }).sort({ ano_cerimonia: -1 }).limit(1); ```


------

11. Quem ganhou o primeiro Oscar para Melhor Atriz? Em que ano?

R: Para a categoria Atriz, foi Janet Gaynor, em 1928. Por outro lado, para de fato a cateroria de Melhor Atriz, foi Mikey Madison, em 2025.

Q: ``` db.registros.find({ categoria: "ACTRESS", vencedor: "true" }).sort({ ano_cerimonia: 1 }).limit(1); ``` <br>
ou <br>
 ``` db.registros.find({ categoria: "Best Actress", vencedor: "true" }).sort({ ano_cerimonia: 1 }).limit(1); ```
 
------

12. Na campo "Vencedor", altere todos os valores com "true" para 1 e todos os valores "false" para 0.

R: A alteração foi feita! O retorno efetuado pelo MongoDB shell foi:
```
{
  acknowledged: true,
  insertedId: null,
  matchedCount: 8528,
  modifiedCount: 8528,
  upsertedCount: 0
}
```

Q: ```
db.registros.updateMany({ vencedor: "true" }, { $set: { vencedor: 1 } });
db.registros.updateMany({ vencedor: "false" }, { $set: { vencedor: 0 } });
```
------

13. Em qual edição do Oscar "Crash" concorreu ao Oscar?

R: na 78º edição

Q: ``` db.registros.find({ nome_do_filme: "Crash" }, { cerimonia: 1}); ```
//retone a cerimônia = 1 = true

------

14. O filme Central do Brasil aparece no Oscar?

R: Sim.

Q: ``` db.registros.find({ nome_do_filme: "Central Station" }).count() > 0; ```
//operador de comparação, pois se for maior que zero a quantidade de vezes, significa que aparece, então retorna true, senão retornaria false. <br>
ou<br>
``` db.registros.find({ nome_do_filme: "Central Station" }).count(); ```
//retorna 2 (pois foi indicado ao oscar em duas categorias)

------

15. Inclua no banco 3 filmes que nunca foram nem nomeados ao Oscar, mas que merecem ser.

R: 3 vezes

Q:

------

16. Denzel Washington já ganhou algum Oscar?

R: 3 vezes

Q:

------

17. Quais os filmes que ganharam o Oscar de Melhor Filme?

R: 3 vezes

Q:

------

18. Sidney Poitier foi o primeiro ator negro a ser indicado ao Oscar. Em que ano ele foi indicado? Por qual filme?

R: 3 vezes

Q:

------

19. Quais os filmes que ganharam o Oscar de Melhor Filme e Melhor Diretor na mesma cerimonia?

R: 3 vezes

Q:

------

20. Denzel Washington e Jamie Foxx já concorreram ao Oscar no mesmo ano?

R: 3 vezes

Q:
