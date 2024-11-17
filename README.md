# DraftAssets
This is a repository of Pokémon Sprites with the intention of using them for draft docs. 

Sets of sprites have referencing for the original sprites, with resized versions and greyscale versions being run through python using the module Pillow.

Sprites are stored under the following structure:
`branch -> gen -> game/format -> update -> colour/grey -> size`

Example 1:
`main/gen9/sv/dlc2/colour/x64/bulbasaur.png` REMOVED

Example 2:
`main/gen9/NatDex/Home/grey/x128/bulbasaur.png`

Full urls are prefixed with `aaaaa` so sprites can be referenced at `https::`

Anything on the main branch is considered volatile. If you want to be sure the sprites stay the same long term then consider changing this to one of the versioned branches that when created should be constant.
## Name Scheme
All the names use the Pokémon Showdown format with a few exceptions, listed below, usually made due to avoid filename/link issues:

A list of all names can be found either in [markdown format](./Pokemon/NamesIndex.md) or in [csv](./Pokemon/NamesIndex.csv) which can be imported into google sheets. 
### Name Adjustments
*Showdown Name -> Sprite Name*

Gen 1
- Farfetch’d -> Farfetchd
- Farfetch’d-Galar -> Farfetchd-Galar
- Mr. Mime -> Mr.Mime
- Mr. Mime-Galar -> Mr.Mime-Galar
Gen 4
- Mime Jr. -> MimeJr.
Gen 6
- Vivillon-Icy Snow -> Vivillon-IcySnow
- Vivillon-High Plains -> Vivillon-HighPlains
- Furfrou-La Reine -> Furfrou-LaReine
Gen 7
- Type: Null -> TypeNull
- Tapu Koko -> TapuKoko
- Tapu Lele -> TapuLele
- Tapu Bulu -> TapuBulu
- Tapu Fini -> TapuFini
Gen 8
- Sirfetch’d -> Sirfetchd
- Mr. Rime -> Mr.Rime
Gen 9
- Great Tusk -> GreatTusk
- Scream Tail -> ScreamTail
- Brute Bonnet -> BruteBonnet
- Flutter Mane -> FlutterMane
- Slither Wing -> SlitherWing
- Sandy Shocks -> SandyShocks
- Iron Treads -> IronTreads
- Iron Bundle -> IronBundle
- Iron Hands -> IronHands
- Iron Jugulis -> IronJugulis
- Iron Moth -> IronMoth
- Iron Thorns -> IronThorns
- Roaring Moon -> RoaringMoon
- Iron Valiant -> IronValiant
- Walking Wake -> WalkingWake
- Iron Leaves -> IronLeaves
- Gouging Fire -> GougingFire
- Raging Bolt -> RagingBolt
- Iron Boulder -> IronBoulder
- Iron Crown -> IronCrown
