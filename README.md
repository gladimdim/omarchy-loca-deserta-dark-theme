[![Built for Omarchy](https://raw.githubusercontent.com/tcballard/omarchy-badges/85f859029e236e784e7b05ada6dbe73506d07a91/badges/v1/built-for-omarchy.svg)](https://github.com/tcballard/omarchy-badges)

# Loca Deserta Dark

```bash
omarchy theme install https://github.com/gladimdim/omarchy-loca-deserta-dark-theme.git
omarchy theme set "Loca Deserta Dark"
```

An [Omarchy](https://omarchy.org) theme for the far-future **Loca Deserta** universe:
the Hetmanate Federation, its heavy assault Terminators, and the void between stars.

![Preview](preview.png)

The preview is the usual Omarchy 4-app collage: Neovim, btop, terminal, and Files
tiled over the default wallpaper, with the Omarchy bar along the bottom.

Companion theme: [Loca Deserta Light](https://github.com/gladimdim/omarchy-loca-deserta-light-theme).

## Palette

Derived from the Terminator illustrations: carbon void, battle-plate steel,
lunar regolith, and starlight corona highlights.

| Role       | Hex       | Source                                   |
|------------|-----------|------------------------------------------|
| background | `#10100f` | carbon void, deep lunar shadow           |
| foreground | `#d1cdc9` | Terminator battle-plate, lunar regolith  |
| accent     | `#ece8e5` | starlight corona, pinpoint glare         |
| yellow     | `#dbb471` | weathered brass, hazard markings         |
| orange     | `#d47844` | muzzle flare, engine burn                |
| red        | `#d95750` | targeting laser, combat warning          |
| green      | `#88ad7c` | tactical HUD phosphor, night optics      |
| cyan       | `#5ca3ad` | plasma bolt                              |
| blue       | `#6b93b8` | cold void, tempered steel                |
| magenta    | `#a688b5` | sensor bloom, ion wake                   |

Active window borders run a 45° gradient from starlight corona white to weathered titanium plate.

Omarchy generates terminal, Neovim, btop, and the rest of the desktop from
`colors.toml` when the theme is applied.

## Shell

White outlines on every Omarchy shell surface so chrome reads as starlight on
carbon void:

- launcher, menus, notifications, popups, and tooltips
- lock screen and polkit password fields (wrong-password stays red)
- image-picker slices and control rows (buttons, tabs, dropdowns)

Icons use **Yaru-blue**.

## Backgrounds

Hetmanate Terminator assault troopers on lunar and airless-asteroid operations.
Every wallpaper carries a pixel-font **LOCA DESERTA SCIFI** title and a
tactical HUD plate with a universe lore quote.

1. `Background.webp` — infantry rifleman Danylo Morozenko against an eclipse. *"Let their plasma melt our armor — they will never melt our spite! Hold the breach!"* Defense of the Kodak Orbital Bastion, year 318 SE.
2. `Terminator-2.webp` — mounted Sotnyk Omelian Nechypura. *"Forward, Cossacks! Death walks ahead, but eternal glory walks with us!"* Battle for the Perekop Frontier, year 320 SE.
3. `Terminators-3.webp` — cavalry squadron charging under a full planet. Same Kodak Orbital Bastion quote as the infantry plate.
4. `Terminators-4.webp` — trio of heavy Cossack cyber-cavalry at a gallop. *"Do not look for the landing shuttles, brothers! We leave this rock as victors — or as cosmic dust!"* Kurinnyi Otaman Taras Honta, Third Siege of the Myriad Red Plains, year 321 SE.
5. `Terminator-5.webp` — heavy cyber-lancer. *"They outnumber us ten to one? Excellent! Now we don't have to waste time aiming!"* Haiduk Desiatnyk Lukash Zhuravel, void skirmish at asteroid Khorol, year 320 SE.
6. `Trio-Terminator.webp` — trio of heavy Cossack cyber-cavalry. *"If the engines fail — ram them! If the cannons burst — board them! While a single Cossack breathes, the Hetmanate never yields!"* Otaman Petro Perebyinis, fleet clash at the Capricorn Expanse, year 320 SE.

Cycle with `omarchy theme bg next` (or Super+Ctrl+Space).

## Credits

Art and universe by Dmytro Gladkyi, from the
[Loca Deserta SciFi](https://github.com/gladimdim/LocaDesertaSciFi) vault.
