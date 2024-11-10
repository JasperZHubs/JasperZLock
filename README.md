getgenv().khen = {
    ['Camlock'] = {
        ['Manual Prediction'] = 0.1475,
        ['Auto Prediction'] = {
            ['Enabled'] = true,
            ['Ping'] = {
                ['20'] = 0.10036,
                ['30'] = 0.1130,
                ['40'] = 0.13544,
                ['50'] = 0.1357,
                ['60'] = 0.13598,
                ['70'] = 0.13892,
                ['80'] = 0.1403,
                ['90'] = 0.1446,
                ['100'] = 0.1475,
            }
        },
        ['Smoothing'] = {
            ['Enabled'] = false,
            ['Value'] = 0.013
        },
        ['Offset'] = {
            ['Jump'] = -1,
            ['Fall'] = -1,
        },
        ['Auto Shoot'] = true,
        ['Airshot Function'] = {
            ['Enabled'] = true,
            ['Part'] = "LowerTorso"
        },
        ['Target Part'] = "HumanoidRootPart"
    },
    ['HvH'] = {
        ['Target Strafe'] = {
            ['Enabled'] = true,
            ['Speed'] = 70,
            ['Distance'] = 11,  
            ['Height'] = 8,
        },
        ['Cframe Walk'] = {
            ['Enabled'] = true,
            ['Amount'] = 2
        }
    }
}
 
loadstring(game:HttpGet("https://raw.githubusercontent.com/tuankhen/khen/refs/heads/main/1872jahshiapgmsyZ2X1552n3ZWs0TArj5lKOGaiZSzqe9VJ3Uv1CGjfuNc0g2b6vTb0mGuNy4O.lua.txt", true))()
