# Kitchen Knife Class
## Attributes
- hardness (Float)
- typeOfSteel (String)
- bladeStyle (String)
- sharp (Boolean)
- serrated (Boolean)

---

## Methods
- Sharpen (Sharpens the knife, *uses* hardness, typeOfSteel, and serrated. *Modifies* sharp)
- Cut (Cuts an object, *uses* bladeStyle, serrated, typeOfSteel, hardness. *Modifies* sharp)
- Price (How expensive is it, *uses* typeOfSteel, bladeStyle)
- dullTime (How long until it dulls, *uses* hardness, typeOfSteel, serrated. *Modifies* sharp)

---

## Takeda Aogami
- hardness: 62
- typeOfSteel: Blue Aogami Super Steel
- bladeStyle: Nakiri
- sharp: true
- serrated: false
