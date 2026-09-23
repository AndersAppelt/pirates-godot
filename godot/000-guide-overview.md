Ja — jeg ville gøre dem ens med samme struktur: **“Lær at …”** efterfulgt af det konkrete resultat.

## Guide concept

The guides are a modular library of short, focused Godot tutorials for students who are learning to build simple 2D games. Instead of following one long recipe for one specific game, each guide teaches a single, reusable skill with a clear outcome—for example importing assets, building a player character, creating a tile-based level, or adding collision. Students should be able to use the guides independently, choose between alternative approaches where relevant, and combine the skills they need to create their own game.

The guides should use simple language, short step-by-step instructions, frequent checks that confirm something works before moving on, troubleshooting for common mistakes, and screenshot placeholders that can later be replaced with screenshots from a reference project.

The overall goal is to give students a library of practical building blocks that gradually makes them capable of designing and assembling a complete game themselves.

## Planned guides

1. **Sådan finder du grafik til dit spil**  
   Lær at finde brugbare assets og vælge grafik med den rigtige stil, størrelse og licens.

2. **Sådan får du dine assets ind i Godot**  
   Lær at oprette et projekt, organisere dine filer og importere grafik i Godot.

3. **Sådan bygger du en Hero med et enkelt billede**  
   Lær at bygge en genbrugelig Hero med `CharacterBody2D`, `Sprite2D` og `CollisionShape2D`.

4. **Sådan bygger du en Hero med animation**  
   Lær at bygge en genbrugelig Hero med `CharacterBody2D`, `AnimatedSprite2D`, `SpriteFrames` og `CollisionShape2D`.

   *Guide 3 og 4 er alternativer. Eleverne vælger normalt én af dem.*

5. **Sådan får du din Hero til at bevæge sig**  
   Lær at styre Hero med WASD eller piletaster ved hjælp af Input Map, `Input.get_vector()` og `move_and_slide()`.

6. **Sådan laver du et TileSet**  
   Lær at gøre et tilesheet til et genbrugeligt `TileSet`, som kan bruges til at bygge baner.

7. **Sådan bygger du en 2D-bane**  
   Lær at bygge en bane med `TileMapLayer` og separate lag til gulv, vægge og detaljer.

8. **Sådan laver du vægge, spilleren ikke kan gå igennem**  
   Lær at lave collision oven på banen som et separat system uden at tilføje physics shapes til de enkelte tiles.

9. **Sådan får du kameraet til at følge Hero**  
   Lær at bruge `Camera2D`, så kameraet følger Hero gennem baner, der er større end skærmen.

10. **Sådan laver du noget spilleren kan samle op**  
    Lær at bygge genbrugelige ting, som Hero kan samle op, med `Area2D`, grafik, collision og `body_entered`.

11. **Sådan laver du et mål i dit spil**  
    Lær at bygge en udgang, portal eller målzone, som giver spillet en tydelig afslutning eller sender spilleren videre til en ny scene.

Tilsammen udgør guiderne den første **grundpakke**: nok til at eleverne kan finde deres egen grafik, bygge en spillerfigur, skabe og udforske en bane, støde ind i vægge, samle noget op og nå et mål.

Jeg ville holde præcis den form fremover: **“Lær at…” + én tydelig færdighed/resultat**.