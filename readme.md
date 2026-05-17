## 5-row Chromatic Button Accordion analysis using .musicxml files

1. Export a `.musicxml` file from music software such as [Musescore](https://musescore.org/en/download) or [Sibelius](https://www.avid.com/sibelius)

2. Place the `.musicxml` file into the `musicxml` folder

3. Open `musicxml analysis.Rmd`

4. Run the code chunks to output a `.png` chart into the `charts` folder

## Example .musicxml files

Example `.musicxml` files are provided for two tunes in the `musicxml` folder:

Angus Macleod [https://thesession.org/tunes/13488](https://thesession.org/tunes/13488)

Hills of Lorne [https://thesession.org/tunes/15197](https://thesession.org/tunes/15197)

## Interpreting the charts

The darker the red markings around a button, the more frequently that note is played in the tune. 

The distance travelled between two adjacent buttons in the same row is taken to be '1 unit'.

Under each chart is a calculation for how far one travels across the buttons, in the order that they are played in the tune, using only the specified rows of buttons. This does not take into account any repeated sections within the tune.

The smaller the distance traveled using the stated rows suggests that those are the optimum rows to consider using when playing the tune.

The analysis does not take account of the position of the fingers that one might use to play the notes in their required order, or the size of one's hand.

Hence this analysis is really only valid for a player with possibly one or two actual fingers!



