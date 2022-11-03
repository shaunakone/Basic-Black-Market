Go to QB-Shops and go to Config.lua

Paste and change values for your weapons

["illegal_Weapons"] = {
        [1] = {
            name = "weapon_knife",
            price = 250,
            amount = 250,
            info = {},
            type = "item",
            slot = 1,
        },
    },

-- add whatever you want, copy paste the template. 






Paste this into your Config.Locations.

-- Blackmarket
    ["blackmarketLocation"] = {
        ["label"] = "BlackMarket",
        ["coords"] = vector4(262.7, -1783.6, 27.11, 217.78), -- Changes location 
        ["ped"] = 'a_m_m_indian_01', -- Changes the ped
        ["scenario"] = "WORLD_HUMAN_STAND_MOBILE",
        ["radius"] = 1.5,
        ["targetIcon"] = "fas fa-shopping-basket",
        ["targetLabel"] = "Open Shop",
        ["products"] = Config.Products["illegal_Weapons"],
        ["showblip"] = true,
        ["blipsprite"] = 52,
        ["blipcolor"] = 0
    },
