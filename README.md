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

R: ``` {_id: 'DIRECTING', total_indicacoes: 469}
{_id: 'FILM EDITING', total_indicacoes: 450}
{_id: 'ACTRESS IN A SUPPORTING ROLE', total_indicacoes: 440}
{_id: 'ACTOR IN A SUPPORTING ROLE', total_indicacoes: 440}
{_id: 'DOCUMENTARY (Short Subject)', total_indicacoes: 378}
{_id: 'BEST PICTURE', total_indicacoes: 371} ```

<details> <summary>Veja a resposata completa expandindo aqui.</summary>
```
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

R:``` db.registros.aggregate([
  { $match: { categoria: { $in: ["ACTOR", "ACTRESS", "Best Actress", "Best Actor","ACTRESS IN A SUPPORTING ROLE","ACTOR IN A SUPPORTING ROLE"] } } },
  { $group: { _id: "$nome_do_indicado", indicacoes: { $sum: 1 } } },
  { $match: { indicacoes: { $gt: 1 } } }
]); ```

Q:

------

9. A série de filmes Toy Story ganhou Oscars em quais anos?


R: 

Q:

------

10. A partir de que ano que a categoria "Actress" deixa de existir?

R: 

Q:

------

11. Quem ganhou o primeiro Oscar para Melhor Atriz? Em que ano?

R: 3 vezes

Q:

------

12. Na campo "Vencedor", altere todos os valores com "true" para 1 e todos os valores "false" para 0.

R: 3 vezes

Q:

------

13. Em qual edição do Oscar "Crash" concorreu ao Oscar?

R: 3 vezes

Q:

------

14. O filme Central do Brasil aparece no Oscar?

R: 3 vezes

Q:

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
