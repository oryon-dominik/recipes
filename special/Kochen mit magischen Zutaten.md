Menu: Kochen mit magischen Zutaten.

> inspiriert durch eine - in der öffentlichen Kritik weitgehend unpopuläre - kalifornische Kochshow eines größeren Streaminganbieters

---
*Vorspeisen*

Angegrillte Brokkolisprossen mit Pfirsich Habanero Salsa, Aprikosenschalotten und Queso Fresco. Etwas Öl und Blütenstaub.

Feigen mit Gorgonzola an Balsamicobutter
Radieschen, Dill, Melone

Avocado Gurkensalat an Lemonhaze mit Sea-Flavored Clean Pasta

Beyond-Meat roher Tartar mit in Krautöl pochiertem Eigelb
Cracker mit Mehlwürmern und Grashüpfern

Sojachorizo in infusioniertem Blätterteig mit Honig-Sriracha garniert mit in Bourbon eingelegten Kirschen, Pistazienkruste. Dazu Feldsalat mit etwas Essig und Blumenblüten

Gegrilltes Croque Madame mit Tomatenchutney, Bechamel, Wachtelei und Schnittlauch

Pflanzenblätter eingearbeitet in Chilaquiles mit Knoblauchcreme, Olivenöl und grüner Salsa

Fünf Käse Blumenkohl Maccaroni mit Apfelgarnitur

---
*Hauptgang*

Gegrillter Pakchoi + Mangold mit Chili Salat, dazu
 in Bananenblätter gewickelter WildLachs der mit weißer Limettencurrybutter bestrichen wurde

Gegrillte Zwiebeln zu einer Kokosnussinfusionspolenta mit angegrilltem Swiss Chard

---
*Dessert*

Zitrone, Rosmarin und magischer Honig auf Pekanüssen

In Mezcal marinierte gegrillte Mango mit gestreckter Kondensmilch auf gebuttertem Vanillekekstortenboden mit Sahne und Pistazien

Mangogelee auf Beeren auf Spekulatiuscrumble mit Kokosnussschlagsahne und Lemonhaze.

Blätterteigsamoroso mit in magischem Honig geschlagenem Ziegenkäse und Haselnuss Gremolata mit viel Sauce aus Feigenkonfitüre und Nelken-Hazegastrique.

Waffeln aus kandierten Süßkartoffeln mit geräuchertem Ahornsirup, Walnüssen und Kürbisblüten

---
*basis Butter*

Backofen vorheizen auf 105-110°.
Stängel & Blätter hacken, Knospen grinden.
Material in einem Bratschlauch 30-40 Minuten decarboxylieren.
Abkühlen lassen.

Auf kleiner Temperatur in einem Topf 250g gesalzene Butter (wegen des höheren Schmelzpunktes) mit den Zutaten langsam aufkochen, bis sich kleinste Bläschen bilden, dabei 300ml Wasser portionsweise hinzugeben, um das Material zu bedecken, es soll ja nichts verbrennen.

Das ganze so lange köcheln, wie es geht (5-10h und mehr).
Dabei pro Stunde etwa 50-100ml Wasser hinzugeben, das immer genügend Flüssigkeit vorhanden ist.

Durch ein feines Tuch in eine Schüssel abseihen, einglasen und in den Kühlschrank stellen.

```python
def cook(
	g: int = 5,  # how much we add to the butter (in grams)
	potential: int = 20,  # how 'strong' is the breed (percentage share of Ingredients)
	butter: int = 250,  # default weight of one package of butter in g
):
	"""
	For an average to advanced experience take 10-30 mg per portion.
	So calculate carefully how much your dish should be cooked with.

	For the defaults the result is 4 mg per gram butter.
	A full tablespoon already has ~14grams (~= 50mg potent substance!)

	THAT IS A LOT and usually enough for 3-5 people. Be careful.
	Less is more ;-)
	"""
        # Processing steps usually involve decarboxylation, which reduces potential by around 10%.
	total_mg = (g * 1000) * (potential/100)
	a_gram_butter_has_mg = total_mg / butter 
	# This is the dose in mg per gram butter.
	return a_gram_butter_has_mg

```

#receipe #rezept #kochen #cooking #menü #special
