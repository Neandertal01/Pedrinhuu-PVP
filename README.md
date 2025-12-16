
local G2L = {};

-- StarterGui.Pedrinhuu Menu PVP
G2L["1"] = Instance.new("ScreenGui", game:GetService("Players").LocalPlayer:WaitForChild("PlayerGui"));
G2L["1"]["IgnoreGuiInset"] = true;
G2L["1"]["ScreenInsets"] = Enum.ScreenInsets.DeviceSafeInsets;
G2L["1"]["Name"] = [[Pedrinhuu Menu PVP]];
G2L["1"]["ZIndexBehavior"] = Enum.ZIndexBehavior.Sibling;


-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu
G2L["2"] = Instance.new("Frame", G2L["1"]);
G2L["2"]["BorderSizePixel"] = 0;
G2L["2"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2"]["Size"] = UDim2.new(0, 755, 0, 431);
G2L["2"]["Position"] = UDim2.new(0.4081, 0, 0.22522, 0);
G2L["2"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2"]["Name"] = [[PedrinhuuMenu]];


-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Drag
G2L["3"] = Instance.new("LocalScript", G2L["2"]);
G2L["3"]["Name"] = [[Drag]];


-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Bypass
G2L["4"] = Instance.new("LocalScript", G2L["2"]);
G2L["4"]["Name"] = [[Bypass]];


-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.UICorner
G2L["5"] = Instance.new("UICorner", G2L["2"]);



-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Title 2
G2L["6"] = Instance.new("TextLabel", G2L["2"]);
G2L["6"]["TextWrapped"] = true;
G2L["6"]["BorderSizePixel"] = 0;
G2L["6"]["TextSize"] = 14;
G2L["6"]["TextScaled"] = true;
G2L["6"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["6"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["6"]["TextColor3"] = Color3.fromRGB(199, 0, 0);
G2L["6"]["BackgroundTransparency"] = 1;
G2L["6"]["Size"] = UDim2.new(0, 173, 0, 34);
G2L["6"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["6"]["Text"] = [[Melhor Menu para PVP]];
G2L["6"]["Name"] = [[Title 2]];
G2L["6"]["Position"] = UDim2.new(0, 0, 0.0348, 0);


-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Title
G2L["7"] = Instance.new("TextLabel", G2L["2"]);
G2L["7"]["TextWrapped"] = true;
G2L["7"]["BorderSizePixel"] = 0;
G2L["7"]["TextSize"] = 14;
G2L["7"]["TextScaled"] = true;
G2L["7"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["7"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["7"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["7"]["BackgroundTransparency"] = 1;
G2L["7"]["Size"] = UDim2.new(0, 173, 0, 34);
G2L["7"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["7"]["Text"] = [[PEDRINHUU PVP]];
G2L["7"]["Name"] = [[Title]];


-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Buttons
G2L["8"] = Instance.new("Frame", G2L["2"]);
G2L["8"]["BorderSizePixel"] = 0;
G2L["8"]["BackgroundColor3"] = Color3.fromRGB(36, 36, 36);
G2L["8"]["Size"] = UDim2.new(0, 755, 0, 42);
G2L["8"]["Position"] = UDim2.new(0, 0, 0.11369, 0);
G2L["8"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["8"]["Name"] = [[Buttons]];


-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Buttons.Aim
G2L["9"] = Instance.new("TextButton", G2L["8"]);
G2L["9"]["BorderSizePixel"] = 0;
G2L["9"]["TextSize"] = 14;
G2L["9"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["9"]["BackgroundColor3"] = Color3.fromRGB(255, 0, 0);
G2L["9"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["9"]["Size"] = UDim2.new(0, 92, 0, 32);
G2L["9"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["9"]["Text"] = [[Aimbot/Aimlock]];
G2L["9"]["Name"] = [[Aim]];
G2L["9"]["Position"] = UDim2.new(0.09007, 0, 0.11861, 0);


-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Buttons.Aim.UICorner
G2L["a"] = Instance.new("UICorner", G2L["9"]);



-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Buttons.Aim.LocalScript
G2L["b"] = Instance.new("LocalScript", G2L["9"]);



-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Buttons.Visual
G2L["c"] = Instance.new("TextButton", G2L["8"]);
G2L["c"]["BorderSizePixel"] = 0;
G2L["c"]["TextSize"] = 14;
G2L["c"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["c"]["BackgroundColor3"] = Color3.fromRGB(255, 0, 0);
G2L["c"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["c"]["Size"] = UDim2.new(0, 92, 0, 32);
G2L["c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["c"]["Text"] = [[ESP/VISUAL]];
G2L["c"]["Name"] = [[Visual]];
G2L["c"]["Position"] = UDim2.new(0.32848, 0, 0.11861, 0);


-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Buttons.Visual.UICorner
G2L["d"] = Instance.new("UICorner", G2L["c"]);



-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Buttons.Visual.LocalScript
G2L["e"] = Instance.new("LocalScript", G2L["c"]);



-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Buttons.FPS
G2L["f"] = Instance.new("TextButton", G2L["8"]);
G2L["f"]["BorderSizePixel"] = 0;
G2L["f"]["TextSize"] = 14;
G2L["f"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["f"]["BackgroundColor3"] = Color3.fromRGB(255, 0, 0);
G2L["f"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["f"]["Size"] = UDim2.new(0, 92, 0, 32);
G2L["f"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["f"]["Text"] = [[DESEMPENHO]];
G2L["f"]["Name"] = [[FPS]];
G2L["f"]["Position"] = UDim2.new(0.54967, 0, 0.11861, 0);


-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Buttons.FPS.UICorner
G2L["10"] = Instance.new("UICorner", G2L["f"]);



-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Buttons.FPS.LocalScript
G2L["11"] = Instance.new("LocalScript", G2L["f"]);



-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Buttons.Outros
G2L["12"] = Instance.new("TextButton", G2L["8"]);
G2L["12"]["BorderSizePixel"] = 0;
G2L["12"]["TextSize"] = 14;
G2L["12"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["12"]["BackgroundColor3"] = Color3.fromRGB(255, 0, 0);
G2L["12"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["12"]["Size"] = UDim2.new(0, 92, 0, 32);
G2L["12"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["12"]["Text"] = [[OUTROS]];
G2L["12"]["Name"] = [[Outros]];
G2L["12"]["Position"] = UDim2.new(0.78808, 0, 0.11861, 0);


-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Buttons.Outros.UICorner
G2L["13"] = Instance.new("UICorner", G2L["12"]);



-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Buttons.Outros.LocalScript
G2L["14"] = Instance.new("LocalScript", G2L["12"]);



-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.AimFrame
G2L["15"] = Instance.new("Frame", G2L["2"]);
G2L["15"]["Visible"] = false;
G2L["15"]["BorderSizePixel"] = 0;
G2L["15"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["15"]["Size"] = UDim2.new(0, 755, 0, 340);
G2L["15"]["Position"] = UDim2.new(0, 0, 0.21114, 0);
G2L["15"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["15"]["Name"] = [[AimFrame]];
G2L["15"]["BackgroundTransparency"] = 1;


-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.AimFrame.aimbut
G2L["16"] = Instance.new("TextButton", G2L["15"]);
G2L["16"]["BorderSizePixel"] = 0;
G2L["16"]["TextSize"] = 14;
G2L["16"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["16"]["BackgroundColor3"] = Color3.fromRGB(171, 0, 0);
G2L["16"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["16"]["Size"] = UDim2.new(0, 29, 0, 29);
G2L["16"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["16"]["Text"] = [[]];
G2L["16"]["Name"] = [[aimbut]];
G2L["16"]["Position"] = UDim2.new(0.01589, 0, 0.03957, 0);


-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.AimFrame.aimbut.LocalScript
G2L["17"] = Instance.new("LocalScript", G2L["16"]);



-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.AimFrame.aimbut.UICorner
G2L["18"] = Instance.new("UICorner", G2L["16"]);



-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.AimFrame.aimbut.TextLabel
G2L["19"] = Instance.new("TextLabel", G2L["16"]);
G2L["19"]["TextWrapped"] = true;
G2L["19"]["BorderSizePixel"] = 0;
G2L["19"]["TextSize"] = 14;
G2L["19"]["TextScaled"] = true;
G2L["19"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["19"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["19"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["19"]["BackgroundTransparency"] = 1;
G2L["19"]["Size"] = UDim2.new(0, 159, 0, 29);
G2L["19"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["19"]["Text"] = [[Ativar Aimbot]];
G2L["19"]["Position"] = UDim2.new(1, 0, 0, 0);


-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.AimFrame.aimlock
G2L["1a"] = Instance.new("TextButton", G2L["15"]);
G2L["1a"]["BorderSizePixel"] = 0;
G2L["1a"]["TextSize"] = 14;
G2L["1a"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1a"]["BackgroundColor3"] = Color3.fromRGB(171, 0, 0);
G2L["1a"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["1a"]["Size"] = UDim2.new(0, 29, 0, 29);
G2L["1a"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1a"]["Text"] = [[]];
G2L["1a"]["Name"] = [[aimlock]];
G2L["1a"]["Position"] = UDim2.new(0.01589, 0, 0.19545, 0);


-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.AimFrame.aimlock.LocalScript
G2L["1b"] = Instance.new("LocalScript", G2L["1a"]);



-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.AimFrame.aimlock.UICorner
G2L["1c"] = Instance.new("UICorner", G2L["1a"]);



-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.AimFrame.aimlock.TextLabel
G2L["1d"] = Instance.new("TextLabel", G2L["1a"]);
G2L["1d"]["TextWrapped"] = true;
G2L["1d"]["BorderSizePixel"] = 0;
G2L["1d"]["TextSize"] = 14;
G2L["1d"]["TextScaled"] = true;
G2L["1d"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1d"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["1d"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1d"]["BackgroundTransparency"] = 1;
G2L["1d"]["Size"] = UDim2.new(0, 159, 0, 29);
G2L["1d"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1d"]["Text"] = [[Ativar AimLock]];
G2L["1d"]["Position"] = UDim2.new(1, 0, 0, 0);


-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.AimFrame.auxilio
G2L["1e"] = Instance.new("TextButton", G2L["15"]);
G2L["1e"]["BorderSizePixel"] = 0;
G2L["1e"]["TextSize"] = 14;
G2L["1e"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1e"]["BackgroundColor3"] = Color3.fromRGB(171, 0, 0);
G2L["1e"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["1e"]["Size"] = UDim2.new(0, 29, 0, 29);
G2L["1e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1e"]["Text"] = [[]];
G2L["1e"]["Name"] = [[auxilio]];
G2L["1e"]["Position"] = UDim2.new(0.01589, 0, 0.35721, 0);


-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.AimFrame.auxilio.LocalScript
G2L["1f"] = Instance.new("LocalScript", G2L["1e"]);



-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.AimFrame.auxilio.UICorner
G2L["20"] = Instance.new("UICorner", G2L["1e"]);



-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.AimFrame.auxilio.TextLabel
G2L["21"] = Instance.new("TextLabel", G2L["1e"]);
G2L["21"]["TextWrapped"] = true;
G2L["21"]["BorderSizePixel"] = 0;
G2L["21"]["TextSize"] = 14;
G2L["21"]["TextScaled"] = true;
G2L["21"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["21"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["21"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["21"]["BackgroundTransparency"] = 1;
G2L["21"]["Size"] = UDim2.new(0, 207, 0, 29);
G2L["21"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["21"]["Text"] = [[Ativar AimAssist]];
G2L["21"]["Position"] = UDim2.new(1, 0, 0, 0);


-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.AimFrame.TextLabel
G2L["22"] = Instance.new("TextLabel", G2L["15"]);
G2L["22"]["TextWrapped"] = true;
G2L["22"]["BorderSizePixel"] = 0;
G2L["22"]["TextSize"] = 14;
G2L["22"]["TextScaled"] = true;
G2L["22"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["22"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["22"]["TextColor3"] = Color3.fromRGB(199, 0, 0);
G2L["22"]["BackgroundTransparency"] = 1;
G2L["22"]["Size"] = UDim2.new(0, 352, 0, 45);
G2L["22"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["22"]["Text"] = [[-=======- AIMBOT CONFIG -=======-]];
G2L["22"]["Position"] = UDim2.new(0.47947, 0, 0.01418, 0);


-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.AimFrame.Force
G2L["23"] = Instance.new("TextBox", G2L["15"]);
G2L["23"]["Name"] = [[Force]];
G2L["23"]["BorderSizePixel"] = 0;
G2L["23"]["TextWrapped"] = true;
G2L["23"]["TextSize"] = 14;
G2L["23"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["23"]["TextScaled"] = true;
G2L["23"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["23"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["23"]["PlaceholderText"] = [[0.87]];
G2L["23"]["Size"] = UDim2.new(0, 163, 0, 22);
G2L["23"]["Position"] = UDim2.new(0.60397, 0, 0.21507, 0);
G2L["23"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["23"]["Text"] = [[]];


-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.AimFrame.Force.UICorner
G2L["24"] = Instance.new("UICorner", G2L["23"]);



-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.AimFrame.TextLabel
G2L["25"] = Instance.new("TextLabel", G2L["15"]);
G2L["25"]["TextWrapped"] = true;
G2L["25"]["BorderSizePixel"] = 0;
G2L["25"]["TextSize"] = 14;
G2L["25"]["TextScaled"] = true;
G2L["25"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["25"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["25"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["25"]["BackgroundTransparency"] = 1;
G2L["25"]["Size"] = UDim2.new(0, 89, 0, 28);
G2L["25"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["25"]["Text"] = [[Força]];
G2L["25"]["Position"] = UDim2.new(0.65298, 0, 0.13183, 0);


-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.AimFrame.Range
G2L["26"] = Instance.new("TextBox", G2L["15"]);
G2L["26"]["Name"] = [[Range]];
G2L["26"]["BorderSizePixel"] = 0;
G2L["26"]["TextWrapped"] = true;
G2L["26"]["TextSize"] = 14;
G2L["26"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["26"]["TextScaled"] = true;
G2L["26"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["26"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["26"]["PlaceholderText"] = [[150]];
G2L["26"]["Size"] = UDim2.new(0, 163, 0, 22);
G2L["26"]["Position"] = UDim2.new(0.60397, 0, 0.37684, 0);
G2L["26"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["26"]["Text"] = [[]];


-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.AimFrame.Range.UICorner
G2L["27"] = Instance.new("UICorner", G2L["26"]);



-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.AimFrame.TextLabel
G2L["28"] = Instance.new("TextLabel", G2L["15"]);
G2L["28"]["TextWrapped"] = true;
G2L["28"]["BorderSizePixel"] = 0;
G2L["28"]["TextSize"] = 14;
G2L["28"]["TextScaled"] = true;
G2L["28"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["28"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["28"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["28"]["BackgroundTransparency"] = 1;
G2L["28"]["Size"] = UDim2.new(0, 89, 0, 28);
G2L["28"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["28"]["Text"] = [[Raio]];
G2L["28"]["Position"] = UDim2.new(0.65298, 0, 0.29359, 0);


-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.AimFrame.Distance
G2L["29"] = Instance.new("TextBox", G2L["15"]);
G2L["29"]["Name"] = [[Distance]];
G2L["29"]["BorderSizePixel"] = 0;
G2L["29"]["TextWrapped"] = true;
G2L["29"]["TextSize"] = 14;
G2L["29"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["29"]["TextScaled"] = true;
G2L["29"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["29"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["29"]["PlaceholderText"] = [[300]];
G2L["29"]["Size"] = UDim2.new(0, 163, 0, 22);
G2L["29"]["Position"] = UDim2.new(0.60397, 0, 0.5239, 0);
G2L["29"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["29"]["Text"] = [[]];


-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.AimFrame.Distance.UICorner
G2L["2a"] = Instance.new("UICorner", G2L["29"]);



-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.AimFrame.TextLabel
G2L["2b"] = Instance.new("TextLabel", G2L["15"]);
G2L["2b"]["TextWrapped"] = true;
G2L["2b"]["BorderSizePixel"] = 0;
G2L["2b"]["TextSize"] = 14;
G2L["2b"]["TextScaled"] = true;
G2L["2b"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["2b"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["2b"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["2b"]["BackgroundTransparency"] = 1;
G2L["2b"]["Size"] = UDim2.new(0, 89, 0, 28);
G2L["2b"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2b"]["Text"] = [[Distancia]];
G2L["2b"]["Position"] = UDim2.new(0.65298, 0, 0.44065, 0);


-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.AimFrame.Set
G2L["2c"] = Instance.new("TextButton", G2L["15"]);
G2L["2c"]["TextWrapped"] = true;
G2L["2c"]["BorderSizePixel"] = 0;
G2L["2c"]["TextSize"] = 26;
G2L["2c"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["2c"]["BackgroundColor3"] = Color3.fromRGB(171, 0, 0);
G2L["2c"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["2c"]["Size"] = UDim2.new(0, 218, 0, 29);
G2L["2c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2c"]["Text"] = [[Setar Configurações]];
G2L["2c"]["Name"] = [[Set]];
G2L["2c"]["Position"] = UDim2.new(0.56821, 0, 0.7778, 0);


-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.AimFrame.Set.UICorner
G2L["2d"] = Instance.new("UICorner", G2L["2c"]);



-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.AimFrame.TextLabel
G2L["2e"] = Instance.new("TextLabel", G2L["15"]);
G2L["2e"]["TextWrapped"] = true;
G2L["2e"]["BorderSizePixel"] = 0;
G2L["2e"]["TextSize"] = 14;
G2L["2e"]["TextScaled"] = true;
G2L["2e"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["2e"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["2e"]["TextColor3"] = Color3.fromRGB(199, 0, 0);
G2L["2e"]["BackgroundTransparency"] = 1;
G2L["2e"]["Size"] = UDim2.new(0, 352, 0, 45);
G2L["2e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2e"]["Text"] = [[-=======- AIMLOCK CONFIG -=======-]];
G2L["2e"]["Position"] = UDim2.new(0.01589, 0, 0.48771, 0);


-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.AimFrame.Cabeca
G2L["2f"] = Instance.new("TextButton", G2L["15"]);
G2L["2f"]["TextWrapped"] = true;
G2L["2f"]["BorderSizePixel"] = 0;
G2L["2f"]["TextSize"] = 26;
G2L["2f"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["2f"]["BackgroundColor3"] = Color3.fromRGB(171, 0, 0);
G2L["2f"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["2f"]["Size"] = UDim2.new(0, 199, 0, 23);
G2L["2f"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2f"]["Text"] = [[Head]];
G2L["2f"]["Name"] = [[Cabeca]];
G2L["2f"]["Position"] = UDim2.new(0.11656, 0, 0.7131, 0);


-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.AimFrame.Cabeca.LocalScript
G2L["30"] = Instance.new("LocalScript", G2L["2f"]);



-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.AimFrame.Cabeca.UICorner
G2L["31"] = Instance.new("UICorner", G2L["2f"]);



-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.AimFrame.TextLabel
G2L["32"] = Instance.new("TextLabel", G2L["15"]);
G2L["32"]["TextWrapped"] = true;
G2L["32"]["BorderSizePixel"] = 0;
G2L["32"]["TextSize"] = 14;
G2L["32"]["TextScaled"] = true;
G2L["32"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["32"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["32"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["32"]["BackgroundTransparency"] = 1;
G2L["32"]["Size"] = UDim2.new(0, 89, 0, 28);
G2L["32"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["32"]["Text"] = [[Lock in]];
G2L["32"]["Position"] = UDim2.new(0.1894, 0, 0.58771, 0);


-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.AimFrame.Corpo
G2L["33"] = Instance.new("TextButton", G2L["15"]);
G2L["33"]["TextWrapped"] = true;
G2L["33"]["BorderSizePixel"] = 0;
G2L["33"]["TextSize"] = 26;
G2L["33"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["33"]["BackgroundColor3"] = Color3.fromRGB(171, 0, 0);
G2L["33"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["33"]["Size"] = UDim2.new(0, 199, 0, 23);
G2L["33"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["33"]["Text"] = [[Torso]];
G2L["33"]["Name"] = [[Corpo]];
G2L["33"]["Position"] = UDim2.new(0.11656, 0, 0.81604, 0);


-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.AimFrame.Corpo.LocalScript
G2L["34"] = Instance.new("LocalScript", G2L["33"]);



-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.AimFrame.Corpo.UICorner
G2L["35"] = Instance.new("UICorner", G2L["33"]);



-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.AimFrame.NPC
G2L["36"] = Instance.new("TextButton", G2L["15"]);
G2L["36"]["TextWrapped"] = true;
G2L["36"]["BorderSizePixel"] = 0;
G2L["36"]["TextSize"] = 26;
G2L["36"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["36"]["BackgroundColor3"] = Color3.fromRGB(171, 0, 0);
G2L["36"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["36"]["Size"] = UDim2.new(0, 163, 0, 29);
G2L["36"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["36"]["Text"] = [[Ativar em NPC]];
G2L["36"]["Name"] = [[NPC]];
G2L["36"]["Position"] = UDim2.new(0.60397, 0, 0.64545, 0);


-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.AimFrame.NPC.UICorner
G2L["37"] = Instance.new("UICorner", G2L["36"]);



-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Visuais
G2L["38"] = Instance.new("Frame", G2L["2"]);
G2L["38"]["Visible"] = false;
G2L["38"]["BorderSizePixel"] = 0;
G2L["38"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["38"]["Size"] = UDim2.new(0, 755, 0, 340);
G2L["38"]["Position"] = UDim2.new(0, 0, 0.21114, 0);
G2L["38"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["38"]["Name"] = [[Visuais]];
G2L["38"]["BackgroundTransparency"] = 1;


-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Visuais.esp
G2L["39"] = Instance.new("TextButton", G2L["38"]);
G2L["39"]["BorderSizePixel"] = 0;
G2L["39"]["TextSize"] = 14;
G2L["39"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["39"]["BackgroundColor3"] = Color3.fromRGB(171, 0, 0);
G2L["39"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["39"]["Size"] = UDim2.new(0, 29, 0, 29);
G2L["39"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["39"]["Text"] = [[]];
G2L["39"]["Name"] = [[esp]];
G2L["39"]["Position"] = UDim2.new(0.01457, 0, 0.03918, 0);


-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Visuais.esp.LocalScript
G2L["3a"] = Instance.new("LocalScript", G2L["39"]);



-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Visuais.esp.UICorner
G2L["3b"] = Instance.new("UICorner", G2L["39"]);



-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Visuais.esp.TextLabel
G2L["3c"] = Instance.new("TextLabel", G2L["39"]);
G2L["3c"]["TextWrapped"] = true;
G2L["3c"]["BorderSizePixel"] = 0;
G2L["3c"]["TextSize"] = 14;
G2L["3c"]["TextScaled"] = true;
G2L["3c"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["3c"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["3c"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["3c"]["BackgroundTransparency"] = 1;
G2L["3c"]["Size"] = UDim2.new(0, 135, 0, 29);
G2L["3c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["3c"]["Text"] = [[Ativar ESP]];
G2L["3c"]["Position"] = UDim2.new(1, 0, 0, 0);


-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Visuais.t esp
G2L["3d"] = Instance.new("TextButton", G2L["38"]);
G2L["3d"]["BorderSizePixel"] = 0;
G2L["3d"]["TextSize"] = 14;
G2L["3d"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["3d"]["BackgroundColor3"] = Color3.fromRGB(171, 0, 0);
G2L["3d"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["3d"]["Size"] = UDim2.new(0, 29, 0, 29);
G2L["3d"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["3d"]["Text"] = [[]];
G2L["3d"]["Name"] = [[t esp]];
G2L["3d"]["Position"] = UDim2.new(0.01457, 0, 0.20682, 0);


-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Visuais.t esp.LocalScript
G2L["3e"] = Instance.new("LocalScript", G2L["3d"]);



-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Visuais.t esp.UICorner
G2L["3f"] = Instance.new("UICorner", G2L["3d"]);



-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Visuais.t esp.TextLabel
G2L["40"] = Instance.new("TextLabel", G2L["3d"]);
G2L["40"]["TextWrapped"] = true;
G2L["40"]["BorderSizePixel"] = 0;
G2L["40"]["TextSize"] = 14;
G2L["40"]["TextScaled"] = true;
G2L["40"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["40"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["40"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["40"]["BackgroundTransparency"] = 1;
G2L["40"]["Size"] = UDim2.new(0, 165, 0, 29);
G2L["40"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["40"]["Text"] = [[Ativar Team ESP]];
G2L["40"]["Position"] = UDim2.new(1, 0, 0, 0);


-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Visuais.l esp
G2L["41"] = Instance.new("TextButton", G2L["38"]);
G2L["41"]["BorderSizePixel"] = 0;
G2L["41"]["TextSize"] = 14;
G2L["41"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["41"]["BackgroundColor3"] = Color3.fromRGB(171, 0, 0);
G2L["41"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["41"]["Size"] = UDim2.new(0, 29, 0, 29);
G2L["41"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["41"]["Text"] = [[]];
G2L["41"]["Name"] = [[l esp]];
G2L["41"]["Position"] = UDim2.new(0.01457, 0, 0.38035, 0);


-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Visuais.l esp.LocalScript
G2L["42"] = Instance.new("LocalScript", G2L["41"]);



-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Visuais.l esp.UICorner
G2L["43"] = Instance.new("UICorner", G2L["41"]);



-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Visuais.l esp.TextLabel
G2L["44"] = Instance.new("TextLabel", G2L["41"]);
G2L["44"]["TextWrapped"] = true;
G2L["44"]["BorderSizePixel"] = 0;
G2L["44"]["TextSize"] = 14;
G2L["44"]["TextScaled"] = true;
G2L["44"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["44"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["44"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["44"]["BackgroundTransparency"] = 1;
G2L["44"]["Size"] = UDim2.new(0, 133, 0, 29);
G2L["44"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["44"]["Text"] = [[Linhas ESP]];
G2L["44"]["Position"] = UDim2.new(1, 0, 0, 0);


-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Visuais.m esp
G2L["45"] = Instance.new("TextButton", G2L["38"]);
G2L["45"]["BorderSizePixel"] = 0;
G2L["45"]["TextSize"] = 14;
G2L["45"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["45"]["BackgroundColor3"] = Color3.fromRGB(171, 0, 0);
G2L["45"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["45"]["Size"] = UDim2.new(0, 29, 0, 29);
G2L["45"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["45"]["Text"] = [[]];
G2L["45"]["Name"] = [[m esp]];
G2L["45"]["Position"] = UDim2.new(0.01457, 0, 0.56565, 0);


-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Visuais.m esp.LocalScript
G2L["46"] = Instance.new("LocalScript", G2L["45"]);



-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Visuais.m esp.UICorner
G2L["47"] = Instance.new("UICorner", G2L["45"]);



-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Visuais.m esp.TextLabel
G2L["48"] = Instance.new("TextLabel", G2L["45"]);
G2L["48"]["TextWrapped"] = true;
G2L["48"]["BorderSizePixel"] = 0;
G2L["48"]["TextSize"] = 14;
G2L["48"]["TextScaled"] = true;
G2L["48"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["48"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["48"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["48"]["BackgroundTransparency"] = 1;
G2L["48"]["Size"] = UDim2.new(0, 133, 0, 29);
G2L["48"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["48"]["Text"] = [[Mostar Times]];
G2L["48"]["Position"] = UDim2.new(1, 0, 0, 0);


-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Visuais.d esp
G2L["49"] = Instance.new("TextButton", G2L["38"]);
G2L["49"]["BorderSizePixel"] = 0;
G2L["49"]["TextSize"] = 14;
G2L["49"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["49"]["BackgroundColor3"] = Color3.fromRGB(171, 0, 0);
G2L["49"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["49"]["Size"] = UDim2.new(0, 29, 0, 29);
G2L["49"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["49"]["Text"] = [[]];
G2L["49"]["Name"] = [[d esp]];
G2L["49"]["Position"] = UDim2.new(0.01457, 0, 0.74212, 0);


-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Visuais.d esp.LocalScript
G2L["4a"] = Instance.new("LocalScript", G2L["49"]);



-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Visuais.d esp.UICorner
G2L["4b"] = Instance.new("UICorner", G2L["49"]);



-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Visuais.d esp.TextLabel
G2L["4c"] = Instance.new("TextLabel", G2L["49"]);
G2L["4c"]["TextWrapped"] = true;
G2L["4c"]["BorderSizePixel"] = 0;
G2L["4c"]["TextSize"] = 14;
G2L["4c"]["TextScaled"] = true;
G2L["4c"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["4c"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["4c"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["4c"]["BackgroundTransparency"] = 1;
G2L["4c"]["Size"] = UDim2.new(0, 196, 0, 29);
G2L["4c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["4c"]["Text"] = [[Mostar Distancia]];
G2L["4c"]["Position"] = UDim2.new(1, 0, 0, 0);


-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Visuais.mira fixa
G2L["4d"] = Instance.new("TextButton", G2L["38"]);
G2L["4d"]["BorderSizePixel"] = 0;
G2L["4d"]["TextSize"] = 14;
G2L["4d"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["4d"]["BackgroundColor3"] = Color3.fromRGB(171, 0, 0);
G2L["4d"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["4d"]["Size"] = UDim2.new(0, 29, 0, 29);
G2L["4d"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["4d"]["Text"] = [[]];
G2L["4d"]["Name"] = [[mira fixa]];
G2L["4d"]["Position"] = UDim2.new(0.48079, 0, 0.03918, 0);


-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Visuais.mira fixa.LocalScript
G2L["4e"] = Instance.new("LocalScript", G2L["4d"]);



-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Visuais.mira fixa.UICorner
G2L["4f"] = Instance.new("UICorner", G2L["4d"]);



-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Visuais.mira fixa.TextLabel
G2L["50"] = Instance.new("TextLabel", G2L["4d"]);
G2L["50"]["TextWrapped"] = true;
G2L["50"]["BorderSizePixel"] = 0;
G2L["50"]["TextSize"] = 14;
G2L["50"]["TextScaled"] = true;
G2L["50"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["50"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["50"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["50"]["BackgroundTransparency"] = 1;
G2L["50"]["Size"] = UDim2.new(0, 135, 0, 29);
G2L["50"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["50"]["Text"] = [[Mira Fixa]];
G2L["50"]["Position"] = UDim2.new(1, 0, 0, 0);


-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Visuais.SetFov
G2L["51"] = Instance.new("TextBox", G2L["38"]);
G2L["51"]["Name"] = [[SetFov]];
G2L["51"]["BorderSizePixel"] = 0;
G2L["51"]["TextWrapped"] = true;
G2L["51"]["TextSize"] = 14;
G2L["51"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["51"]["TextScaled"] = true;
G2L["51"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["51"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["51"]["PlaceholderText"] = [[Set Fov...]];
G2L["51"]["Size"] = UDim2.new(0, 213, 0, 32);
G2L["51"]["Position"] = UDim2.new(0.48079, 0, 0.35331, 0);
G2L["51"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["51"]["Text"] = [[]];


-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Visuais.SetFov.UICorner
G2L["52"] = Instance.new("UICorner", G2L["51"]);



-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Visuais.FOV
G2L["53"] = Instance.new("TextButton", G2L["38"]);
G2L["53"]["BorderSizePixel"] = 0;
G2L["53"]["TextSize"] = 14;
G2L["53"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["53"]["BackgroundColor3"] = Color3.fromRGB(171, 0, 0);
G2L["53"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["53"]["Size"] = UDim2.new(0, 29, 0, 29);
G2L["53"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["53"]["Text"] = [[]];
G2L["53"]["Name"] = [[FOV]];
G2L["53"]["Position"] = UDim2.new(0.48079, 0, 0.20524, 0);


-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Visuais.FOV.LocalScript
G2L["54"] = Instance.new("LocalScript", G2L["53"]);



-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Visuais.FOV.UICorner
G2L["55"] = Instance.new("UICorner", G2L["53"]);



-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Visuais.FOV.TextLabel
G2L["56"] = Instance.new("TextLabel", G2L["53"]);
G2L["56"]["TextWrapped"] = true;
G2L["56"]["BorderSizePixel"] = 0;
G2L["56"]["TextSize"] = 14;
G2L["56"]["TextScaled"] = true;
G2L["56"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["56"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["56"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["56"]["BackgroundTransparency"] = 1;
G2L["56"]["Size"] = UDim2.new(0, 135, 0, 29);
G2L["56"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["56"]["Text"] = [[Mudar FOV]];
G2L["56"]["Position"] = UDim2.new(1, 0, 0, 0);


-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Fps
G2L["57"] = Instance.new("Frame", G2L["2"]);
G2L["57"]["Visible"] = false;
G2L["57"]["BorderSizePixel"] = 0;
G2L["57"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["57"]["Size"] = UDim2.new(0, 755, 0, 340);
G2L["57"]["Position"] = UDim2.new(0, 0, 0.21114, 0);
G2L["57"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["57"]["Name"] = [[Fps]];
G2L["57"]["BackgroundTransparency"] = 1;


-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Fps.eff
G2L["58"] = Instance.new("TextButton", G2L["57"]);
G2L["58"]["BorderSizePixel"] = 0;
G2L["58"]["TextSize"] = 14;
G2L["58"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["58"]["BackgroundColor3"] = Color3.fromRGB(171, 0, 0);
G2L["58"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["58"]["Size"] = UDim2.new(0, 29, 0, 29);
G2L["58"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["58"]["Text"] = [[]];
G2L["58"]["Name"] = [[eff]];
G2L["58"]["Position"] = UDim2.new(0.01457, 0, 0.03918, 0);


-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Fps.eff.LocalScript
G2L["59"] = Instance.new("LocalScript", G2L["58"]);



-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Fps.eff.UICorner
G2L["5a"] = Instance.new("UICorner", G2L["58"]);



-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Fps.eff.TextLabel
G2L["5b"] = Instance.new("TextLabel", G2L["58"]);
G2L["5b"]["TextWrapped"] = true;
G2L["5b"]["BorderSizePixel"] = 0;
G2L["5b"]["TextSize"] = 14;
G2L["5b"]["TextScaled"] = true;
G2L["5b"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["5b"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["5b"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["5b"]["BackgroundTransparency"] = 1;
G2L["5b"]["Size"] = UDim2.new(0, 187, 0, 29);
G2L["5b"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["5b"]["Text"] = [[Desativar Efeitos]];
G2L["5b"]["Position"] = UDim2.new(1, 0, 0, 0);


-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Fps.eff
G2L["5c"] = Instance.new("TextButton", G2L["57"]);
G2L["5c"]["BorderSizePixel"] = 0;
G2L["5c"]["TextSize"] = 14;
G2L["5c"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["5c"]["BackgroundColor3"] = Color3.fromRGB(171, 0, 0);
G2L["5c"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["5c"]["Size"] = UDim2.new(0, 29, 0, 29);
G2L["5c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["5c"]["Text"] = [[]];
G2L["5c"]["Name"] = [[eff]];
G2L["5c"]["Position"] = UDim2.new(0.01457, 0, 0.20977, 0);


-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Fps.eff.LocalScript
G2L["5d"] = Instance.new("LocalScript", G2L["5c"]);



-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Fps.eff.UICorner
G2L["5e"] = Instance.new("UICorner", G2L["5c"]);



-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Fps.eff.TextLabel
G2L["5f"] = Instance.new("TextLabel", G2L["5c"]);
G2L["5f"]["TextWrapped"] = true;
G2L["5f"]["BorderSizePixel"] = 0;
G2L["5f"]["TextSize"] = 14;
G2L["5f"]["TextScaled"] = true;
G2L["5f"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["5f"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["5f"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["5f"]["BackgroundTransparency"] = 1;
G2L["5f"]["Size"] = UDim2.new(0, 208, 0, 29);
G2L["5f"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["5f"]["Text"] = [[Desativar Particulas]];
G2L["5f"]["Position"] = UDim2.new(1, 0, 0, 0);


-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Fps.eff
G2L["60"] = Instance.new("TextButton", G2L["57"]);
G2L["60"]["BorderSizePixel"] = 0;
G2L["60"]["TextSize"] = 14;
G2L["60"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["60"]["BackgroundColor3"] = Color3.fromRGB(171, 0, 0);
G2L["60"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["60"]["Size"] = UDim2.new(0, 29, 0, 29);
G2L["60"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["60"]["Text"] = [[]];
G2L["60"]["Name"] = [[eff]];
G2L["60"]["Position"] = UDim2.new(0.01457, 0, 0.39506, 0);


-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Fps.eff.LocalScript
G2L["61"] = Instance.new("LocalScript", G2L["60"]);



-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Fps.eff.UICorner
G2L["62"] = Instance.new("UICorner", G2L["60"]);



-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Fps.eff.TextLabel
G2L["63"] = Instance.new("TextLabel", G2L["60"]);
G2L["63"]["TextWrapped"] = true;
G2L["63"]["BorderSizePixel"] = 0;
G2L["63"]["TextSize"] = 14;
G2L["63"]["TextScaled"] = true;
G2L["63"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["63"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["63"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["63"]["BackgroundTransparency"] = 1;
G2L["63"]["Size"] = UDim2.new(0, 208, 0, 29);
G2L["63"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["63"]["Text"] = [[Desativar Sombras]];
G2L["63"]["Position"] = UDim2.new(1, 0, 0, 0);


-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Fps.eff
G2L["64"] = Instance.new("TextButton", G2L["57"]);
G2L["64"]["BorderSizePixel"] = 0;
G2L["64"]["TextSize"] = 14;
G2L["64"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["64"]["BackgroundColor3"] = Color3.fromRGB(171, 0, 0);
G2L["64"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["64"]["Size"] = UDim2.new(0, 29, 0, 29);
G2L["64"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["64"]["Text"] = [[]];
G2L["64"]["Name"] = [[eff]];
G2L["64"]["Position"] = UDim2.new(0.01457, 0, 0.57741, 0);


-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Fps.eff.LocalScript
G2L["65"] = Instance.new("LocalScript", G2L["64"]);



-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Fps.eff.UICorner
G2L["66"] = Instance.new("UICorner", G2L["64"]);



-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Fps.eff.TextLabel
G2L["67"] = Instance.new("TextLabel", G2L["64"]);
G2L["67"]["TextWrapped"] = true;
G2L["67"]["BorderSizePixel"] = 0;
G2L["67"]["TextSize"] = 14;
G2L["67"]["TextScaled"] = true;
G2L["67"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["67"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["67"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["67"]["BackgroundTransparency"] = 1;
G2L["67"]["Size"] = UDim2.new(0, 208, 0, 29);
G2L["67"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["67"]["Text"] = [[Desativar Materiais]];
G2L["67"]["Position"] = UDim2.new(1, 0, 0, 0);


-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Fps.eff
G2L["68"] = Instance.new("TextButton", G2L["57"]);
G2L["68"]["BorderSizePixel"] = 0;
G2L["68"]["TextSize"] = 14;
G2L["68"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["68"]["BackgroundColor3"] = Color3.fromRGB(171, 0, 0);
G2L["68"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["68"]["Size"] = UDim2.new(0, 29, 0, 29);
G2L["68"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["68"]["Text"] = [[]];
G2L["68"]["Name"] = [[eff]];
G2L["68"]["Position"] = UDim2.new(0.01457, 0, 0.76565, 0);


-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Fps.eff.LocalScript
G2L["69"] = Instance.new("LocalScript", G2L["68"]);



-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Fps.eff.UICorner
G2L["6a"] = Instance.new("UICorner", G2L["68"]);



-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Fps.eff.TextLabel
G2L["6b"] = Instance.new("TextLabel", G2L["68"]);
G2L["6b"]["TextWrapped"] = true;
G2L["6b"]["BorderSizePixel"] = 0;
G2L["6b"]["TextSize"] = 14;
G2L["6b"]["TextScaled"] = true;
G2L["6b"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["6b"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["6b"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["6b"]["BackgroundTransparency"] = 1;
G2L["6b"]["Size"] = UDim2.new(0, 148, 0, 29);
G2L["6b"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["6b"]["Text"] = [[Modo Batata]];
G2L["6b"]["Position"] = UDim2.new(1, 0, 0, 0);


-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Fps.FPSDisplay
G2L["6c"] = Instance.new("TextLabel", G2L["57"]);
G2L["6c"]["TextWrapped"] = true;
G2L["6c"]["BorderSizePixel"] = 0;
G2L["6c"]["TextSize"] = 14;
G2L["6c"]["TextScaled"] = true;
G2L["6c"]["BackgroundColor3"] = Color3.fromRGB(171, 0, 0);
G2L["6c"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["6c"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["6c"]["Size"] = UDim2.new(0, 140, 0, 41);
G2L["6c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["6c"]["Text"] = [[0]];
G2L["6c"]["Name"] = [[FPSDisplay]];
G2L["6c"]["Position"] = UDim2.new(0.40643, 0, 0.14818, 0);


-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Fps.FPSDisplay.LocalScript
G2L["6d"] = Instance.new("LocalScript", G2L["6c"]);



-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Fps.FPSDisplay.UICorner
G2L["6e"] = Instance.new("UICorner", G2L["6c"]);



-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Fps.TextLabel
G2L["6f"] = Instance.new("TextLabel", G2L["57"]);
G2L["6f"]["TextWrapped"] = true;
G2L["6f"]["BorderSizePixel"] = 0;
G2L["6f"]["TextSize"] = 14;
G2L["6f"]["TextScaled"] = true;
G2L["6f"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["6f"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["6f"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["6f"]["BackgroundTransparency"] = 1;
G2L["6f"]["Size"] = UDim2.new(0, 115, 0, 38);
G2L["6f"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["6f"]["Text"] = [[FPS]];
G2L["6f"]["Position"] = UDim2.new(0.42384, 0, 0.03771, 0);


-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Outers
G2L["70"] = Instance.new("Frame", G2L["2"]);
G2L["70"]["BorderSizePixel"] = 0;
G2L["70"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["70"]["Size"] = UDim2.new(0, 755, 0, 340);
G2L["70"]["Position"] = UDim2.new(0, 0, 0.21114, 0);
G2L["70"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["70"]["Name"] = [[Outers]];
G2L["70"]["BackgroundTransparency"] = 1;


-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Outers.TextLabel
G2L["71"] = Instance.new("TextLabel", G2L["70"]);
G2L["71"]["TextWrapped"] = true;
G2L["71"]["BorderSizePixel"] = 0;
G2L["71"]["TextSize"] = 14;
G2L["71"]["TextScaled"] = true;
G2L["71"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["71"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["71"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["71"]["BackgroundTransparency"] = 1;
G2L["71"]["Size"] = UDim2.new(0, 201, 0, 38);
G2L["71"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["71"]["Text"] = [[Painel Feito Por:]];
G2L["71"]["Position"] = UDim2.new(0.02781, 0, 0.03771, 0);


-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Outers.Pedrinhuu On Top
G2L["72"] = Instance.new("TextLabel", G2L["70"]);
G2L["72"]["TextWrapped"] = true;
G2L["72"]["BorderSizePixel"] = 0;
G2L["72"]["TextSize"] = 14;
G2L["72"]["TextScaled"] = true;
G2L["72"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["72"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["72"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["72"]["BackgroundTransparency"] = 1;
G2L["72"]["Size"] = UDim2.new(0, 269, 0, 51);
G2L["72"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["72"]["Text"] = [[Pedrinhuu Scripts]];
G2L["72"]["Name"] = [[Pedrinhuu On Top]];
G2L["72"]["Position"] = UDim2.new(0.02781, 0, 0.14947, 0);


-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Outers.Pedrinhuu On Top.LocalScript
G2L["73"] = Instance.new("LocalScript", G2L["72"]);



-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Outers.Change Title
G2L["74"] = Instance.new("TextLabel", G2L["70"]);
G2L["74"]["TextWrapped"] = true;
G2L["74"]["BorderSizePixel"] = 0;
G2L["74"]["TextSize"] = 14;
G2L["74"]["TextScaled"] = true;
G2L["74"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["74"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["74"]["TextColor3"] = Color3.fromRGB(255, 0, 0);
G2L["74"]["BackgroundTransparency"] = 1;
G2L["74"]["Size"] = UDim2.new(0, 343, 0, 30);
G2L["74"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["74"]["Text"] = [[-=======- CHANGE LOGS -=======-]];
G2L["74"]["Name"] = [[Change Title]];
G2L["74"]["Position"] = UDim2.new(0.50993, 0, 0.03771, 0);


-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Outers.TextLabel
G2L["75"] = Instance.new("TextLabel", G2L["70"]);
G2L["75"]["TextWrapped"] = true;
G2L["75"]["BorderSizePixel"] = 0;
G2L["75"]["TextSize"] = 14;
G2L["75"]["TextScaled"] = true;
G2L["75"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["75"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["75"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["75"]["BackgroundTransparency"] = 1;
G2L["75"]["Size"] = UDim2.new(0, 302, 0, 38);
G2L["75"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["75"]["Text"] = [[Painel Não Atualizado Ainda]];
G2L["75"]["Position"] = UDim2.new(0.54702, 0, 0.14947, 0);


-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Outers.TextLabel
G2L["76"] = Instance.new("TextLabel", G2L["70"]);
G2L["76"]["TextWrapped"] = true;
G2L["76"]["BorderSizePixel"] = 0;
G2L["76"]["TextSize"] = 14;
G2L["76"]["TextTransparency"] = 0.58;
G2L["76"]["TextScaled"] = true;
G2L["76"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["76"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["76"]["TextColor3"] = Color3.fromRGB(255, 0, 0);
G2L["76"]["BackgroundTransparency"] = 1;
G2L["76"]["Size"] = UDim2.new(0, 104, 0, 23);
G2L["76"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["76"]["Text"] = [[Version: V1]];
G2L["76"]["Position"] = UDim2.new(0.05298, 0, 0.89653, 0);


-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Outers.TextLabel
G2L["77"] = Instance.new("TextLabel", G2L["70"]);
G2L["77"]["TextWrapped"] = true;
G2L["77"]["BorderSizePixel"] = 0;
G2L["77"]["TextSize"] = 14;
G2L["77"]["TextTransparency"] = 0.58;
G2L["77"]["TextScaled"] = true;
G2L["77"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["77"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["77"]["TextColor3"] = Color3.fromRGB(255, 0, 0);
G2L["77"]["BackgroundTransparency"] = 1;
G2L["77"]["Size"] = UDim2.new(0, 169, 0, 23);
G2L["77"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["77"]["Text"] = [[Criado em 14/12/2025]];
G2L["77"]["Position"] = UDim2.new(0.21722, 0, 0.89653, 0);


-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Outers.TextLabel
G2L["78"] = Instance.new("TextLabel", G2L["70"]);
G2L["78"]["TextWrapped"] = true;
G2L["78"]["BorderSizePixel"] = 0;
G2L["78"]["TextSize"] = 14;
G2L["78"]["TextTransparency"] = 0.58;
G2L["78"]["TextScaled"] = true;
G2L["78"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["78"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["78"]["TextColor3"] = Color3.fromRGB(255, 0, 0);
G2L["78"]["BackgroundTransparency"] = 1;
G2L["78"]["Size"] = UDim2.new(0, 169, 0, 23);
G2L["78"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["78"]["Text"] = [[Atualizado: Sem Updates]];
G2L["78"]["Position"] = UDim2.new(0.4649, 0, 0.89653, 0);


-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Outers.TextLabel
G2L["79"] = Instance.new("TextLabel", G2L["70"]);
G2L["79"]["TextWrapped"] = true;
G2L["79"]["BorderSizePixel"] = 0;
G2L["79"]["TextSize"] = 14;
G2L["79"]["TextTransparency"] = 0.58;
G2L["79"]["TextScaled"] = true;
G2L["79"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["79"]["FontFace"] = Font.new([[rbxasset://fonts/families/Sarpanch.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["79"]["TextColor3"] = Color3.fromRGB(255, 0, 0);
G2L["79"]["BackgroundTransparency"] = 1;
G2L["79"]["Size"] = UDim2.new(0, 169, 0, 23);
G2L["79"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["79"]["Text"] = [[PEDRINHUU ON TOP 👑]];
G2L["79"]["Position"] = UDim2.new(0.72185, 0, 0.89653, 0);


-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Drag
local function C_3()
local script = G2L["3"];
	local UserInputService = game:GetService("UserInputService")
	local player = game.Players.LocalPlayer
	local gui = player:WaitForChild("PlayerGui")
	local frame = script.Parent -- Coloque o LocalScript dentro do Frame que será arrastável
	
	local dragging = false
	local dragInput, dragStart, startPos
	
	local function update(input)
		local delta = input.Position - dragStart
		frame.Position = UDim2.new(
			startPos.X.Scale,
			startPos.X.Offset + delta.X,
			startPos.Y.Scale,
			startPos.Y.Offset + delta.Y
		)
	end
	
	frame.InputBegan:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch then
			dragging = true
			dragStart = input.Position
			startPos = frame.Position
	
			input.Changed:Connect(function()
				if input.UserInputState == Enum.UserInputState.End then
					dragging = false
				end
			end)
		end
	end)
	
	frame.InputChanged:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
			dragInput = input
		end
	end)
	
	UserInputService.InputChanged:Connect(function(input)
		if input == dragInput and dragging then
			update(input)
		end
	end)
	
end;
task.spawn(C_3);
-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Bypass
local function C_4()
local script = G2L["4"];
	local frame = script.Parent
	
	-- força visibilidade inicial
	frame.Visible = true
	
	-- watchdog
	frame:GetPropertyChangedSignal("Visible"):Connect(function()
		if frame.Visible == false then
			frame.Visible = true
		end
	end)
	
	local frame = script.Parent
	local parent = frame.Parent
	
	frame.AncestryChanged:Connect(function(_, newParent)
		if not newParent then
			task.wait()
			frame.Parent = parent
		end
	end)
	
end;
task.spawn(C_4);
-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Buttons.Aim.LocalScript
local function C_b()
local script = G2L["b"];
	local button = script.Parent
	local buttonsFrame = button.Parent
	local screenGui = buttonsFrame.Parent
	
	local aimFrame = screenGui:WaitForChild("AimFrame")
	local fpsFrame = screenGui:WaitForChild("Fps")
	local outersFrame = screenGui:WaitForChild("Outers")
	local visualsFrame = screenGui:WaitForChild("Visuais")
	
	local frames = {aimFrame, fpsFrame, outersFrame, visualsFrame}
	
	button.MouseButton1Click:Connect(function()
		for _, frame in ipairs(frames) do
			frame.Visible = false
		end
	
		aimFrame.Visible = true
	end)
end;
task.spawn(C_b);
-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Buttons.Visual.LocalScript
local function C_e()
local script = G2L["e"];
	local button = script.Parent
	local buttonsFrame = button.Parent
	local screenGui = buttonsFrame.Parent
	
	local aimFrame = screenGui:WaitForChild("AimFrame")
	local fpsFrame = screenGui:WaitForChild("Fps")
	local outersFrame = screenGui:WaitForChild("Outers")
	local visualsFrame = screenGui:WaitForChild("Visuais")
	
	local frames = {aimFrame, fpsFrame, outersFrame, visualsFrame}
	
	button.MouseButton1Click:Connect(function()
		for _, frame in ipairs(frames) do
			frame.Visible = false
		end
	
		visualsFrame.Visible = true
	end)
end;
task.spawn(C_e);
-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Buttons.FPS.LocalScript
local function C_11()
local script = G2L["11"];
	local button = script.Parent
	local buttonsFrame = button.Parent
	local screenGui = buttonsFrame.Parent
	
	local aimFrame = screenGui:WaitForChild("AimFrame")
	local fpsFrame = screenGui:WaitForChild("Fps")
	local outersFrame = screenGui:WaitForChild("Outers")
	local visualsFrame = screenGui:WaitForChild("Visuais")
	
	local frames = {aimFrame, fpsFrame, outersFrame, visualsFrame}
	
	button.MouseButton1Click:Connect(function()
		for _, frame in ipairs(frames) do
			frame.Visible = false
		end
	
		fpsFrame.Visible = true
	end)
end;
task.spawn(C_11);
-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Buttons.Outros.LocalScript
local function C_14()
local script = G2L["14"];
	local button = script.Parent
	local buttonsFrame = button.Parent
	local screenGui = buttonsFrame.Parent
	
	local aimFrame = screenGui:WaitForChild("AimFrame")
	local fpsFrame = screenGui:WaitForChild("Fps")
	local outersFrame = screenGui:WaitForChild("Outers")
	local visualsFrame = screenGui:WaitForChild("Visuais")
	
	local frames = {aimFrame, fpsFrame, outersFrame, visualsFrame}
	
	button.MouseButton1Click:Connect(function()
		for _, frame in ipairs(frames) do
			frame.Visible = false
		end
	
		outersFrame.Visible = true
	end)
end;
task.spawn(C_14);
-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.AimFrame.aimbut.LocalScript
local function C_17()
local script = G2L["17"];
	local Players = game:GetService("Players")
	local RunService = game:GetService("RunService")
	
	local LocalPlayer = Players.LocalPlayer
	local Camera = workspace.CurrentCamera
	
	----------------------------------------------------
	-- UI REFERENCES
	----------------------------------------------------
	local root = script.Parent.Parent -- ajuste se necessário
	
	local toggleButton = script.Parent
	local setButton = root:WaitForChild("Set")
	local npcButton = root:WaitForChild("NPC")
	
	local forceBox = root:WaitForChild("Force")
	local distanceBox = root:WaitForChild("Distance")
	local rangeBox = root:WaitForChild("Range")
	
	----------------------------------------------------
	-- CONFIGS (PADRÃO)
	----------------------------------------------------
	local MAX_PIXELS = 150
	local AIM_SMOOTH = 0.87
	local MAX_STUDS = 300
	local SCAN_NPCS = true
	
	----------------------------------------------------
	-- SYSTEM STATE
	----------------------------------------------------
	local active = false
	local connection = nil
	local ui = nil
	
	----------------------------------------------------
	-- UTILS
	----------------------------------------------------
	local function clampNumber(value, min, max)
		value = tonumber(value)
		if not value then return nil end
		return math.clamp(value, min, max)
	end
	
	----------------------------------------------------
	-- UI (DOT + CIRCLE)
	----------------------------------------------------
	local function createDot()
		if ui then return end
	
		local g = Instance.new("ScreenGui")
		g.IgnoreGuiInset = true
		g.ResetOnSpawn = false
		g.Name = "CenterDotGui"
		g.Parent = LocalPlayer:WaitForChild("PlayerGui")
	
		-- DOT CENTRAL
		local dot = Instance.new("Frame")
		dot.Name = "CenterDot"
		dot.AnchorPoint = Vector2.new(0.5, 0.5)
		dot.Size = UDim2.new(0, 6, 0, 6)
		dot.Position = UDim2.fromScale(0.5, 0.5)
		dot.BackgroundColor3 = Color3.new(1, 1, 1)
		dot.BorderSizePixel = 0
		dot.Parent = g
	
		-- CÍRCULO DO RAIO (CORRIGIDO)
		local circle = Instance.new("Frame")
		circle.Name = "AimRadius"
		circle.AnchorPoint = Vector2.new(0.5, 0.5)
		circle.BackgroundTransparency = 1
		circle.Size = UDim2.new(0, MAX_PIXELS * 2, 0, MAX_PIXELS * 2)
		circle.Position = UDim2.fromScale(0.5, 0.5)
		circle.Parent = g
	
		local stroke = Instance.new("UIStroke")
		stroke.Thickness = 2
		stroke.Color = Color3.new(1, 1, 1)
		stroke.Transparency = 0.4
		stroke.ApplyStrokeMode = Enum.ApplyStrokeMode.Border
		stroke.Parent = circle
	
		local corner = Instance.new("UICorner")
		corner.CornerRadius = UDim.new(1, 0)
		corner.Parent = circle
	
		ui = g
	end
	
	local function updateCircle()
		if not ui then return end
		local circle = ui:FindFirstChild("AimRadius", true)
		if circle then
			circle.Size = UDim2.new(0, MAX_PIXELS * 2, 0, MAX_PIXELS * 2)
		end
	end
	
	local function removeDot()
		if ui then
			ui:Destroy()
			ui = nil
		end
	end
	
	----------------------------------------------------
	-- TARGETS
	----------------------------------------------------
	local function getTargets()
		local list = {}
	
		for _, plr in ipairs(Players:GetPlayers()) do
			if plr ~= LocalPlayer and plr.Character then
				table.insert(list, plr.Character)
			end
		end
	
		if SCAN_NPCS then
			for _, obj in ipairs(workspace:GetChildren()) do
				if obj:IsA("Model")
					and obj:FindFirstChild("Humanoid")
					and obj:FindFirstChild("Head")
					and not Players:GetPlayerFromCharacter(obj) then
					table.insert(list, obj)
				end
			end
		end
	
		return list
	end
	
	----------------------------------------------------
	-- AIMLOCK CORE
	----------------------------------------------------
	local function getClosestTarget()
		local viewport = Camera.ViewportSize
		local center = Vector2.new(viewport.X / 2, viewport.Y / 2)
	
		local bestPart = nil
		local bestDist = MAX_PIXELS + 0.01
	
		for _, char in ipairs(getTargets()) do
			local head = char:FindFirstChild("Head")
			local hum = char:FindFirstChild("Humanoid")
	
			if head and hum and hum.Health > 0 then
				if (Camera.CFrame.Position - head.Position).Magnitude <= MAX_STUDS then
					local pos = Camera:WorldToViewportPoint(head.Position)
					if pos.Z > 0 then
						local dist = (Vector2.new(pos.X, pos.Y) - center).Magnitude
						if dist < bestDist then
							bestDist = dist
							bestPart = head
						end
					end
				end
			end
		end
	
		return bestPart
	end
	
	----------------------------------------------------
	-- START / STOP
	----------------------------------------------------
	local function startSystem()
		if active then return end
		active = true
	
		createDot()
	
		connection = RunService.RenderStepped:Connect(function()
			if not active then return end
	
			local target = getClosestTarget()
			if target then
				local current = Camera.CFrame
				local goal = CFrame.lookAt(current.Position, target.Position)
				Camera.CFrame = current:Lerp(goal, AIM_SMOOTH)
			end
		end)
	end
	
	local function stopSystem()
		active = false
	
		if connection then
			connection:Disconnect()
			connection = nil
		end
	
		removeDot()
	end
	
	----------------------------------------------------
	-- BUTTONS
	----------------------------------------------------
	toggleButton.MouseButton1Click:Connect(function()
		if active then
			stopSystem()
		else
			startSystem()
		end
	end)
	
	npcButton.MouseButton1Click:Connect(function()
		SCAN_NPCS = not SCAN_NPCS
		npcButton.Text = SCAN_NPCS and "NPC: ON" or "NPC: OFF"
	end)
	
	setButton.MouseButton1Click:Connect(function()
		local force = clampNumber(forceBox.Text, 0, 1)
		if force then AIM_SMOOTH = force end
	
		local pixels = clampNumber(distanceBox.Text, 0, 500)
		if pixels then
			MAX_PIXELS = pixels
			updateCircle()
		end
	
		local studs = clampNumber(rangeBox.Text, 0, 1000)
		if studs then MAX_STUDS = studs end
	
		forceBox:ReleaseFocus()
		distanceBox:ReleaseFocus()
		rangeBox:ReleaseFocus()
	end)
	
end;
task.spawn(C_17);
-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.AimFrame.aimlock.LocalScript
local function C_1b()
local script = G2L["1b"];
	local Players = game:GetService("Players")
	local RunService = game:GetService("RunService")
	
	local player = Players.LocalPlayer
	local playerGui = player:WaitForChild("PlayerGui")
	local camera = workspace.CurrentCamera
	
	------------------------------------------------
	-- CONFIG
	------------------------------------------------
	local DOT_SIZE = 8
	local DOT_COLOR = Color3.fromRGB(255, 20, 20)
	
	local AIM_RADIUS = 25
	local SMOOTHNESS = 0.80
	
	-- alvo padrão
	_G.AimTargetPart = "Head"
	
	------------------------------------------------
	-- CENTER DOT
	------------------------------------------------
	local gui = playerGui:FindFirstChild("CenterDotGui") or Instance.new("ScreenGui")
	gui.Name = "CenterDotGui"
	gui.ResetOnSpawn = false
	gui.IgnoreGuiInset = true
	gui.DisplayOrder = 1000
	gui.Parent = playerGui
	
	local dot = gui:FindFirstChild("CenterDot") or Instance.new("Frame")
	dot.Name = "CenterDot"
	dot.Size = UDim2.fromOffset(DOT_SIZE, DOT_SIZE)
	dot.AnchorPoint = Vector2.new(0.5, 0.5)
	dot.BackgroundColor3 = DOT_COLOR
	dot.BorderSizePixel = 0
	dot.Visible = false
	dot.ZIndex = 9999
	dot.Parent = gui
	
	Instance.new("UICorner", dot).CornerRadius = UDim.new(1, 0)
	
	local function updateDot()
		local vs = camera.ViewportSize
		dot.Position = UDim2.new(0, vs.X / 2, 0, vs.Y / 2)
	end
	
	------------------------------------------------
	-- AIMLOCK
	------------------------------------------------
	local function getClosestTarget()
		local closest
		local shortest = AIM_RADIUS
		local center = camera.ViewportSize / 2
	
		for _, model in ipairs(workspace:GetChildren()) do
			if model:IsA("Model") and model ~= player.Character then
				local humanoid = model:FindFirstChildOfClass("Humanoid")
				local part = model:FindFirstChild(_G.AimTargetPart)
	
				if humanoid and humanoid.Health > 0 and part then
					local pos, onScreen = camera:WorldToViewportPoint(part.Position)
					if onScreen then
						local dist = (Vector2.new(pos.X, pos.Y) - center).Magnitude
						if dist < shortest then
							shortest = dist
							closest = part
						end
					end
				end
			end
		end
	
		return closest
	end
	
	------------------------------------------------
	-- LOOP
	------------------------------------------------
	RunService.RenderStepped:Connect(function()
		if not dot.Visible then return end
	
		updateDot()
	
		local target = getClosestTarget()
		if target then
			local camPos = camera.CFrame.Position
			local newCF = CFrame.new(camPos, target.Position)
			camera.CFrame = camera.CFrame:Lerp(newCF, SMOOTHNESS)
		end
	end)
	
	------------------------------------------------
	-- BOTÃO PRINCIPAL (ON/OFF)
	------------------------------------------------
	local button = script.Parent
	
	button.Activated:Connect(function()
		dot.Visible = not dot.Visible
	end)
	
end;
task.spawn(C_1b);
-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.AimFrame.auxilio.LocalScript
local function C_1f()
local script = G2L["1f"];
	-- Aim Assist do PEDRINHUU
	
	local Players = game:GetService("Players")
	local RunService = game:GetService("RunService")
	
	local player = Players.LocalPlayer
	local playerGui = player:WaitForChild("PlayerGui")
	local camera = workspace.CurrentCamera
	
	------------------------------------------------
	-- CONFIG
	------------------------------------------------
	local DOT_SIZE = 8
	local DOT_COLOR = Color3.fromRGB(255, 20, 20)
	
	local ASSIST_RANGE = 600        -- distância do raycast (studs)
	local ASSIST_SMOOTH = 0.25      -- suavidade da correção
	local ENABLE_NPCS = true
	
	------------------------------------------------
	-- STATE
	------------------------------------------------
	local active = false
	local connection
	
	------------------------------------------------
	-- CENTER DOT
	------------------------------------------------
	local gui = Instance.new("ScreenGui")
	gui.Name = "CenterDotGui"
	gui.ResetOnSpawn = false
	gui.DisplayOrder = 1000
	gui.IgnoreGuiInset = true
	gui.Parent = playerGui
	
	local dot = Instance.new("Frame")
	dot.Name = "CenterDot"
	dot.Size = UDim2.fromOffset(DOT_SIZE, DOT_SIZE)
	dot.AnchorPoint = Vector2.new(0.5, 0.5)
	dot.Position = UDim2.fromScale(0.5, 0.5)
	dot.BackgroundColor3 = DOT_COLOR
	dot.BorderSizePixel = 0
	dot.Visible = false
	dot.ZIndex = 9999
	dot.Parent = gui
	
	Instance.new("UICorner", dot).CornerRadius = UDim.new(1, 0)
	
	------------------------------------------------
	-- RAYCAST PARAMS
	------------------------------------------------
	local rayParams = RaycastParams.new()
	rayParams.FilterType = Enum.RaycastFilterType.Blacklist
	rayParams.IgnoreWater = true
	
	------------------------------------------------
	-- FUNÇÃO PRINCIPAL
	------------------------------------------------
	local function aimAssist()
		local viewport = camera.ViewportSize
		local center = Vector2.new(viewport.X / 2, viewport.Y / 2)
	
		local ray = camera:ViewportPointToRay(center.X, center.Y)
		rayParams.FilterDescendantsInstances = { player.Character }
	
		local result = workspace:Raycast(ray.Origin, ray.Direction * ASSIST_RANGE, rayParams)
		if not result then return end
	
		local hitPart = result.Instance
		if not hitPart then return end
	
		local model = hitPart:FindFirstAncestorOfClass("Model")
		if not model then return end
	
		local humanoid = model:FindFirstChildOfClass("Humanoid")
		if not humanoid or humanoid.Health <= 0 then return end
	
		-- ignora NPC se desativado
		if not ENABLE_NPCS and not Players:GetPlayerFromCharacter(model) then
			return
		end
	
		-- AJUSTA A CÂMERA PARA A PARTE ATUAL MIRADA
		local camPos = camera.CFrame.Position
		local targetCF = CFrame.new(camPos, hitPart.Position)
	
		camera.CFrame = camera.CFrame:Lerp(targetCF, ASSIST_SMOOTH)
	end
	
	------------------------------------------------
	-- LOOP
	------------------------------------------------
	local function start()
		if active then return end
		active = true
		dot.Visible = true
	
		connection = RunService.RenderStepped:Connect(function()
			if active then
				aimAssist()
			end
		end)
	end
	
	local function stop()
		active = false
		dot.Visible = false
	
		if connection then
			connection:Disconnect()
			connection = nil
		end
	end
	
	------------------------------------------------
	-- BOTÃO
	------------------------------------------------
	local button = script.Parent
	
	button.Activated:Connect(function()
		if active then
			stop()
		else
			start()
		end
	end)
	
end;
task.spawn(C_1f);
-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.AimFrame.Cabeca.LocalScript
local function C_30()
local script = G2L["30"];
	script.Parent.Activated:Connect(function()
		_G.AimTargetPart = "Head"
	end)
	
end;
task.spawn(C_30);
-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.AimFrame.Corpo.LocalScript
local function C_34()
local script = G2L["34"];
	script.Parent.Activated:Connect(function()
		_G.AimTargetPart = "Torso"
	end)
	
end;
task.spawn(C_34);
-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Visuais.esp.LocalScript
local function C_3a()
local script = G2L["3a"];
	local Players = game:GetService("Players")
	local Workspace = game:GetService("Workspace")
	
	local button = script.Parent
	local localPlayer = Players.LocalPlayer
	local espEnabled = false
	local highlights = {}
	
	-- Função para verificar se é um personagem válido
	local function isValidCharacter(model)
		return model:FindFirstChild("Humanoid") and model:FindFirstChild("HumanoidRootPart")
	end
	
	-- Função para criar ESP em um modelo
	local function createESP(model)
		if model == localPlayer.Character then return end
		if highlights[model] then return end
	
		local highlight = Instance.new("Highlight")
		highlight.Name = "ESP_Highlight"
		highlight.FillColor = Color3.fromRGB(255, 0, 0)
		highlight.OutlineColor = Color3.fromRGB(255, 255, 255)
		highlight.FillTransparency = 0.5
		highlight.OutlineTransparency = 0
		highlight.Parent = model
	
		highlights[model] = highlight
	end
	
	-- Função para remover ESP de um modelo
	local function removeESP(model)
		if highlights[model] then
			highlights[model]:Destroy()
			highlights[model] = nil
		end
	end
	
	-- Função para escanear e adicionar ESP em todos os personagens
	local function scanWorkspace()
		for _, model in pairs(Workspace:GetDescendants()) do
			if model:IsA("Model") and isValidCharacter(model) and espEnabled then
				createESP(model)
			end
		end
	end
	
	-- Função para ativar ESP
	local function enableESP()
		scanWorkspace()
	
		-- Monitora novos modelos adicionados
		Workspace.DescendantAdded:Connect(function(descendant)
			if espEnabled and descendant:IsA("Model") and isValidCharacter(descendant) then
				task.wait(0.1) -- Espera para garantir que o modelo está completo
				if descendant.Parent then
					createESP(descendant)
				end
			end
		end)
	
		-- Monitora jogadores
		Players.PlayerAdded:Connect(function(player)
			player.CharacterAdded:Connect(function(character)
				if espEnabled then
					createESP(character)
				end
			end)
		end)
	
		-- Adiciona ESP em jogadores existentes
		for _, player in pairs(Players:GetPlayers()) do
			if player.Character and player ~= localPlayer then
				createESP(player.Character)
			end
	
			player.CharacterAdded:Connect(function(character)
				if espEnabled then
					createESP(character)
				end
			end)
		end
	end
	
	-- Função para desativar ESP
	local function disableESP()
		for model, highlight in pairs(highlights) do
			highlight:Destroy()
		end
		highlights = {}
	end
	
	-- Toggle do ESP ao clicar no botão
	button.MouseButton1Click:Connect(function()
		espEnabled = not espEnabled
	
		if espEnabled then
			enableESP()
		else
			disableESP()
		end
	end)
end;
task.spawn(C_3a);
-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Visuais.t esp.LocalScript
local function C_3e()
local script = G2L["3e"];
	local Players = game:GetService("Players")
	local RunService = game:GetService("RunService")
	
	local LocalPlayer = Players.LocalPlayer
	local Button = script.Parent
	
	local espAtivo = false
	local caixas = {}
	
	-- Cria caixa 3D
	local function criarCaixa(character, player)
		if caixas[player] then
			caixas[player]:Destroy()
		end
	
		local hrp = character:WaitForChild("HumanoidRootPart", 5)
		if not hrp then return end
	
		local box = Instance.new("BoxHandleAdornment")
		box.Name = "game.3d"
		box.Adornee = character
		box.AlwaysOnTop = true
		box.ZIndex = 10
		box.Size = character:GetExtentsSize()
		box.Transparency = 0.7
		box.Color3 = player.TeamColor.Color
		box.Parent = hrp
	
		caixas[player] = box
	end
	
	-- Remove todas as caixas
	local function removerESP()
		for _, box in pairs(caixas) do
			if box then
				box:Destroy()
			end
		end
		table.clear(caixas)
	end
	
	-- Verifica e aplica ESP
	local function aplicarESP(player)
		if player == LocalPlayer then return end
		if player.Team == LocalPlayer.Team then return end
		if not player.Character then return end
	
		criarCaixa(player.Character, player)
	end
	
	-- Atualiza todos
	local function atualizarTodos()
		for _, player in ipairs(Players:GetPlayers()) do
			aplicarESP(player)
		end
	end
	
	-- Player entrou
	Players.PlayerAdded:Connect(function(player)
		player.CharacterAdded:Connect(function()
			if espAtivo then
				task.wait(0.3)
				aplicarESP(player)
			end
		end)
	end)
	
	-- Player mudou de time
	Players.PlayerAdded:Connect(function(player)
		player:GetPropertyChangedSignal("Team"):Connect(function()
			if espAtivo then
				removerESP()
				atualizarTodos()
			end
		end)
	end)
	
	-- Atualiza respawn
	for _, player in ipairs(Players:GetPlayers()) do
		player.CharacterAdded:Connect(function()
			if espAtivo then
				task.wait(0.3)
				aplicarESP(player)
			end
		end)
	end
	
	-- Clique do botão (toggle)
	Button.MouseButton1Click:Connect(function()
		espAtivo = not espAtivo
	
		if espAtivo then
			atualizarTodos()
		else
			removerESP()
		end
	end)
	
end;
task.spawn(C_3e);
-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Visuais.l esp.LocalScript
local function C_42()
local script = G2L["42"];
	local button = script.Parent
	local RunService = game:GetService("RunService")
	local Players = game:GetService("Players")
	local LocalPlayer = Players.LocalPlayer
	local Camera = workspace.CurrentCamera
	
	local tracersEnabled = false
	local tracers = {} -- armazenar as linhas criadas
	
	-- Criar linha
	local function createTracer(player)
		if tracers[player] then return end
	
		local line = Drawing.new("Line")
		line.Thickness = 2
		line.Color = Color3.fromRGB(255, 0, 0)
		line.Visible = true
	
		tracers[player] = line
	end
	
	-- Remover linha
	local function removeTracer(player)
		if tracers[player] then
			tracers[player]:Remove()
			tracers[player] = nil
		end
	end
	
	-- Atualizar todas as linhas
	local function update()
		if not tracersEnabled then return end
	
		for _, player in ipairs(Players:GetPlayers()) do
			if player ~= LocalPlayer then
				local char = player.Character
				local root = char and char:FindFirstChild("HumanoidRootPart")
	
				if root then
					local pos, onScreen = Camera:WorldToViewportPoint(root.Position)
	
					if not tracers[player] then
						createTracer(player)
					end
	
					if onScreen then
						local line = tracers[player]
	
						line.From = Vector2.new(Camera.ViewportSize.X/2, Camera.ViewportSize.Y) -- parte inferior da tela
						line.To = Vector2.new(pos.X, pos.Y) -- posição do player
						line.Visible = true
					else
						tracers[player].Visible = false
					end
				else
					removeTracer(player)
				end
			end
		end
	end
	
	-- Loop
	RunService.RenderStepped:Connect(update)
	
	-- Botão (Toggle)
	button.MouseButton1Click:Connect(function()
		tracersEnabled = not tracersEnabled
	
		if not tracersEnabled then
			for _, line in pairs(tracers) do
				line:Remove()
			end
			tracers = {}
		end
	end)
	
end;
task.spawn(C_42);
-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Visuais.m esp.LocalScript
local function C_46()
local script = G2L["46"];
	local Players = game:GetService("Players")
	
	local LocalPlayer = Players.LocalPlayer
	local Button = script.Parent
	
	local espAtivo = false
	local billboards = {}
	
	-- Remove Billboard
	local function remover(player)
		if billboards[player] then
			billboards[player]:Destroy()
			billboards[player] = nil
		end
	end
	
	-- Cria BillboardGui
	local function criarBillboard(player, character)
		if not espAtivo then return end
		if player == LocalPlayer then return end
	
		remover(player)
	
		local head = character:WaitForChild("Head", 5)
		if not head then return end
	
		local billboard = Instance.new("BillboardGui")
		billboard.Name = "game.m"
		billboard.Adornee = head
		billboard.Size = UDim2.new(0, 200, 0, 50)
		billboard.StudsOffset = Vector3.new(0, 2.5, 0)
		billboard.AlwaysOnTop = true
		billboard.Parent = head
	
		local text = Instance.new("TextLabel")
		text.Size = UDim2.new(1, 0, 1, 0)
		text.BackgroundTransparency = 1
		text.TextScaled = true
		text.Font = Enum.Font.Sarpanch
		text.TextStrokeTransparency = 0.3
		text.Text = player.Name .. " [" .. (player.Team and player.Team.Name or "nil") .. "]"
		text.TextColor3 = player.TeamColor.Color
		text.Parent = billboard
	
		billboards[player] = billboard
	end
	
	-- Ativa ESP em todos
	local function ativarESP()
		for _, player in ipairs(Players:GetPlayers()) do
			if player.Character then
				criarBillboard(player, player.Character)
			end
	
			player.CharacterAdded:Connect(function(char)
				if espAtivo then
					task.wait(0.2)
					criarBillboard(player, char)
				end
			end)
	
			player:GetPropertyChangedSignal("Team"):Connect(function()
				if espAtivo and player.Character then
					criarBillboard(player, player.Character)
				end
			end)
		end
	end
	
	-- Remove ESP geral
	local function desativarESP()
		for _, billboard in pairs(billboards) do
			if billboard then billboard:Destroy() end
		end
		table.clear(billboards)
	end
	
	-- Player entrou
	Players.PlayerAdded:Connect(function(player)
		player.CharacterAdded:Connect(function(char)
			if espAtivo then
				task.wait(0.2)
				criarBillboard(player, char)
			end
		end)
	
		player:GetPropertyChangedSignal("Team"):Connect(function()
			if espAtivo and player.Character then
				criarBillboard(player, player.Character)
			end
		end)
	end)
	
	-- Clique do botão (Toggle)
	Button.MouseButton1Click:Connect(function()
		espAtivo = not espAtivo
	
		if espAtivo then
			ativarESP()
		else
			desativarESP()
		end
	end)
	
end;
task.spawn(C_46);
-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Visuais.d esp.LocalScript
local function C_4a()
local script = G2L["4a"];
	local Players = game:GetService("Players")
	local RunService = game:GetService("RunService")
	
	local LocalPlayer = Players.LocalPlayer
	local Button = script.Parent
	
	local espAtivo = false
	local billboards = {}
	local updateConnection
	
	-- Remove Billboard
	local function remover(player)
		if billboards[player] then
			billboards[player]:Destroy()
			billboards[player] = nil
		end
	end
	
	-- Cria BillboardGui de distância
	local function criarDistancia(player, character)
		if not espAtivo then return end
		if player == LocalPlayer then return end
	
		remover(player)
	
		local hrp = character:WaitForChild("HumanoidRootPart", 5)
		if not hrp then return end
	
		local billboard = Instance.new("BillboardGui")
		billboard.Name = "DistanceESP"
		billboard.Adornee = hrp
		billboard.Size = UDim2.new(0, 120, 0, 30)
		billboard.StudsOffset = Vector3.new(0, -3, 0) -- abaixo do player
		billboard.AlwaysOnTop = true
		billboard.Parent = hrp
	
		local text = Instance.new("TextLabel")
		text.Size = UDim2.new(1, 0, 1, 0)
		text.BackgroundTransparency = 1
		text.TextScaled = true
		text.Font = Enum.Font.GothamBold
		text.TextStrokeTransparency = 0.4
		text.TextColor3 = Color3.fromRGB(255, 255, 255)
		text.Parent = billboard
	
		billboards[player] = {
			gui = billboard,
			label = text
		}
	end
	
	-- Atualiza distância em tempo real
	local function atualizarDistancias()
		if not espAtivo then return end
	
		local char = LocalPlayer.Character
		if not char then return end
	
		local localHRP = char:FindFirstChild("HumanoidRootPart")
		if not localHRP then return end
	
		for player, data in pairs(billboards) do
			if player.Character and data.gui then
				local hrp = player.Character:FindFirstChild("HumanoidRootPart")
				if hrp then
					local dist = (localHRP.Position - hrp.Position).Magnitude
					data.label.Text = math.floor(dist) .. " studs"
				end
			end
		end
	end
	
	-- Ativa ESP
	local function ativarESP()
		for _, player in ipairs(Players:GetPlayers()) do
			if player.Character then
				criarDistancia(player, player.Character)
			end
	
			player.CharacterAdded:Connect(function(char)
				if espAtivo then
					task.wait(0.2)
					criarDistancia(player, char)
				end
			end)
		end
	
		updateConnection = RunService.RenderStepped:Connect(atualizarDistancias)
	end
	
	-- Desativa ESP
	local function desativarESP()
		if updateConnection then
			updateConnection:Disconnect()
			updateConnection = nil
		end
	
		for _, data in pairs(billboards) do
			if data.gui then data.gui:Destroy() end
		end
		table.clear(billboards)
	end
	
	-- Player entrou
	Players.PlayerAdded:Connect(function(player)
		player.CharacterAdded:Connect(function(char)
			if espAtivo then
				task.wait(0.2)
				criarDistancia(player, char)
			end
		end)
	end)
	
	-- Clique do botão (Toggle)
	Button.MouseButton1Click:Connect(function()
		espAtivo = not espAtivo
	
		if espAtivo then
			ativarESP()
		else
			desativarESP()
		end
	end)
	
end;
task.spawn(C_4a);
-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Visuais.mira fixa.LocalScript
local function C_4e()
local script = G2L["4e"];
	-- Center Dot controlável por botão
	
	local Players = game:GetService("Players")
	local RunService = game:GetService("RunService")
	
	local DOT_SIZE = 8
	local DOT_COLOR = Color3.fromRGB(255, 255, 255)
	
	local player = Players.LocalPlayer
	local playerGui = player:WaitForChild("PlayerGui")
	
	-- Espera câmera
	local camera
	repeat
		camera = workspace.CurrentCamera
		RunService.RenderStepped:Wait()
	until camera
	
	-- ScreenGui
	local gui = Instance.new("ScreenGui")
	gui.Name = "CenterDotGui"
	gui.ResetOnSpawn = false
	gui.DisplayOrder = 1000
	pcall(function() gui.IgnoreGuiInset = true end)
	gui.Parent = playerGui
	
	-- Dot
	local dot = Instance.new("Frame")
	dot.Name = "CenterDot"
	dot.Size = UDim2.new(0, DOT_SIZE, 0, DOT_SIZE)
	dot.AnchorPoint = Vector2.new(0.5, 0.5)
	dot.BackgroundColor3 = DOT_COLOR
	dot.BorderSizePixel = 0
	dot.Visible = false
	dot.ZIndex = 9999
	dot.Parent = gui
	
	local corner = Instance.new("UICorner")
	corner.CornerRadius = UDim.new(1, 0)
	corner.Parent = dot
	
	-- Atualiza posição
	local function update()
		local vs = camera.ViewportSize
		dot.Position = UDim2.new(0, vs.X / 2, 0, vs.Y / 2)
	end
	
	RunService.RenderStepped:Connect(function()
		if dot.Visible then
			update()
		end
	end)
	
	-- BOTÃO
	local button = script.Parent -- TextButton ou ImageButton
	
	button.Activated:Connect(function()
		dot.Visible = not dot.Visible
		if dot.Visible then
			update()
		end
	end)
	
end;
task.spawn(C_4e);
-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Visuais.FOV.LocalScript
local function C_54()
local script = G2L["54"];
	local button = script.Parent
	local textbox = button.Parent:WaitForChild("SetFov")
	
	local Camera = workspace.CurrentCamera
	
	button.MouseButton1Click:Connect(function()
		local text = textbox.Text
		local value = tonumber(text)
	
		if value then
			Camera.FieldOfView = math.clamp(value, 1, 120)
			print("FOV alterado para:", value)
		else
			warn("Valor inválido na caixa de texto!")
		end
	end)
	
end;
task.spawn(C_54);
-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Fps.eff.LocalScript
local function C_59()
local script = G2L["59"];
	local Lighting = game:GetService("Lighting")
	local button = script.Parent
	
	-- Guarda o estado original dos efeitos
	local effectsCache = {}
	local effectsDisabled = false
	
	-- Tipos de efeitos suportados
	local EFFECT_CLASSES = {
		BloomEffect = true,
		BlurEffect = true,
		ColorCorrectionEffect = true,
		SunRaysEffect = true,
		DepthOfFieldEffect = true,
		Atmosphere = true
	}
	
	local function disableEffects()
		effectsCache = {}
	
		for _, obj in ipairs(Lighting:GetChildren()) do
			if EFFECT_CLASSES[obj.ClassName] then
				if obj:IsA("Atmosphere") then
					-- Atmosphere não tem Enabled
					effectsCache[obj] = obj.Parent
					obj.Parent = nil
				else
					effectsCache[obj] = obj.Enabled
					obj.Enabled = false
				end
			end
		end
	
		effectsDisabled = true
	end
	
	local function enableEffects()
		for obj, state in pairs(effectsCache) do
			if obj and obj.Parent == nil and obj:IsA("Atmosphere") then
				obj.Parent = Lighting
			elseif obj and obj.Parent then
				obj.Enabled = state
			end
		end
	
		effectsCache = {}
		effectsDisabled = false
	end
	
	button.MouseButton1Click:Connect(function()
		if effectsDisabled then
			enableEffects()
			button.Text = ""
		else
			disableEffects()
			button.Text = ""
		end
	end)
	
end;
task.spawn(C_59);
-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Fps.eff.LocalScript
local function C_5d()
local script = G2L["5d"];
	local button = script.Parent
	
	local particlesDisabled = false
	local cache = {}
	
	-- Classes de partículas
	local PARTICLE_CLASSES = {
		ParticleEmitter = true,
		Fire = true,
		Smoke = true,
		Trail = true,
		Sparkles = true
	}
	
	local function disableParticles()
		cache = {}
	
		for _, obj in ipairs(workspace:GetDescendants()) do
			if PARTICLE_CLASSES[obj.ClassName] then
				-- Alguns usam Enabled, outros não
				if obj:IsA("ParticleEmitter") or obj:IsA("Trail") then
					cache[obj] = obj.Enabled
					obj.Enabled = false
				elseif obj:IsA("Fire") or obj:IsA("Smoke") or obj:IsA("Sparkles") then
					cache[obj] = obj.Enabled
					obj.Enabled = false
				end
			end
		end
	
		particlesDisabled = true
	end
	
	local function enableParticles()
		for obj, state in pairs(cache) do
			if obj and obj.Parent then
				obj.Enabled = state
			end
		end
	
		cache = {}
		particlesDisabled = false
	end
	
	button.MouseButton1Click:Connect(function()
		if particlesDisabled then
			enableParticles()
			button.Text = ""
		else
			disableParticles()
			button.Text = ""
		end
	end)
	
end;
task.spawn(C_5d);
-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Fps.eff.LocalScript
local function C_61()
local script = G2L["61"];
	local Lighting = game:GetService("Lighting")
	local button = script.Parent
	
	local shadowsDisabled = false
	local originalGlobalShadows = Lighting.GlobalShadows
	local originalTechnology = Lighting.Technology
	
	local function disableShadows()
		originalGlobalShadows = Lighting.GlobalShadows
		originalTechnology = Lighting.Technology
	
		Lighting.GlobalShadows = false
		Lighting.Technology = Enum.Technology.Compatibility
	
		shadowsDisabled = true
	end
	
	local function enableShadows()
		Lighting.GlobalShadows = originalGlobalShadows
		Lighting.Technology = originalTechnology
	
		shadowsDisabled = false
	end
	
	button.MouseButton1Click:Connect(function()
		if shadowsDisabled then
			enableShadows()
			button.Text = ""
		else
			disableShadows()
			button.Text = ""
		end
	end)
	
end;
task.spawn(C_61);
-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Fps.eff.LocalScript
local function C_65()
local script = G2L["65"];
	local button = script.Parent
	local workspace = game:GetService("Workspace")
	
	local plasticMode = false
	local cache = {}
	
	local function disableMaterials()
		cache = {}
	
		for _, obj in ipairs(workspace:GetDescendants()) do
			if obj:IsA("BasePart") then
				cache[obj] = {
					Material = obj.Material,
					MaterialVariant = obj.MaterialVariant,
					Reflectance = obj.Reflectance
				}
	
				obj.Material = Enum.Material.Plastic
				obj.MaterialVariant = ""
				obj.Reflectance = 0
			end
		end
	
		plasticMode = true
	end
	
	local function enableMaterials()
		for obj, data in pairs(cache) do
			if obj and obj.Parent then
				obj.Material = data.Material
				obj.MaterialVariant = data.MaterialVariant
				obj.Reflectance = data.Reflectance
			end
		end
	
		cache = {}
		plasticMode = false
	end
	
	button.MouseButton1Click:Connect(function()
		if plasticMode then
			enableMaterials()
			button.Text = ""
		else
			disableMaterials()
			button.Text = ""
		end
	end)
	
end;
task.spawn(C_65);
-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Fps.eff.LocalScript
local function C_69()
local script = G2L["69"];
	-- SERVIÇOS
	local Players = game:GetService("Players")
	local Lighting = game:GetService("Lighting")
	local SoundService = game:GetService("SoundService")
	local RunService = game:GetService("RunService")
	local player = Players.LocalPlayer
	local button = script.Parent
	local workspace = game:GetService("Workspace")
	
	-- ESTADO
	local potatoMode = false
	local cache = {}
	local connections = {}
	
	-- ==============================
	-- FUNÇÕES DE DESATIVAÇÃO
	-- ==============================
	
	local function disableVisualEffects()
		for _, obj in ipairs(Lighting:GetChildren()) do
			if obj:IsA("PostEffect") then
				cache[obj] = obj.Enabled
				obj.Enabled = false
			elseif obj:IsA("Atmosphere") then
				cache[obj] = obj.Parent
				obj.Parent = nil
			end
		end
	
		cache.GlobalShadows = Lighting.GlobalShadows
		cache.Technology = Lighting.Technology
	
		Lighting.GlobalShadows = false
		Lighting.Technology = Enum.Technology.Compatibility
	end
	
	local function disableParticles()
		for _, obj in ipairs(workspace:GetDescendants()) do
			if obj:IsA("ParticleEmitter")
				or obj:IsA("Trail")
				or obj:IsA("Fire")
				or obj:IsA("Smoke")
				or obj:IsA("Sparkles") then
				cache[obj] = obj.Enabled
				obj.Enabled = false
			end
		end
	end
	
	local function disableMaterialsAndTextures()
		for _, obj in ipairs(workspace:GetDescendants()) do
			if obj:IsA("BasePart") then
				cache[obj] = {
					Material = obj.Material,
					MaterialVariant = obj.MaterialVariant,
					Reflectance = obj.Reflectance
				}
	
				obj.Material = Enum.Material.Plastic
				obj.MaterialVariant = ""
				obj.Reflectance = 0
			elseif obj:IsA("Texture")
				or obj:IsA("Decal")
				or obj:IsA("SurfaceAppearance") then
				cache[obj] = obj.Transparency or 0
				obj.Transparency = 1
			end
		end
	end
	
	local function disableSounds()
		cache.SoundVolume = SoundService.Volume
		SoundService.Volume = 0
	
		for _, sound in ipairs(workspace:GetDescendants()) do
			if sound:IsA("Sound") then
				cache[sound] = sound.Volume
				sound.Volume = 0
			end
		end
	end
	
	local function reduceRendering()
		settings().Rendering.QualityLevel = Enum.QualityLevel.Level01
	end
	
	-- ==============================
	-- SISTEMA DE OTIMIZAÇÃO CONTÍNUA
	-- ==============================
	
	local function startOptimizer()
		connections.descendant = workspace.DescendantAdded:Connect(function(obj)
			if not potatoMode then return end
	
			if obj:IsA("BasePart") then
				obj.Material = Enum.Material.Plastic
				obj.MaterialVariant = ""
				obj.Reflectance = 0
			elseif obj:IsA("ParticleEmitter")
				or obj:IsA("Trail")
				or obj:IsA("Fire")
				or obj:IsA("Smoke")
				or obj:IsA("Sparkles") then
				obj.Enabled = false
			elseif obj:IsA("Texture")
				or obj:IsA("Decal")
				or obj:IsA("SurfaceAppearance") then
				obj.Transparency = 1
			elseif obj:IsA("Sound") then
				obj.Volume = 0
			end
		end)
	
		connections.loop = RunService.RenderStepped:Connect(function()
			if potatoMode then
				Lighting.GlobalShadows = false
			end
		end)
	end
	
	local function stopOptimizer()
		for _, conn in pairs(connections) do
			conn:Disconnect()
		end
		connections = {}
	end
	
	-- ==============================
	-- RESTAURAÇÃO
	-- ==============================
	
	local function restoreAll()
		for obj, data in pairs(cache) do
			if typeof(data) == "boolean" and obj:IsA("PostEffect") then
				obj.Enabled = data
			elseif typeof(data) == "table" and obj:IsA("BasePart") then
				obj.Material = data.Material
				obj.MaterialVariant = data.MaterialVariant
				obj.Reflectance = data.Reflectance
			elseif typeof(data) == "number" and obj:IsA("Sound") then
				obj.Volume = data
			elseif obj == "GlobalShadows" then
				Lighting.GlobalShadows = data
			elseif obj == "Technology" then
				Lighting.Technology = data
			end
		end
	
		if cache.SoundVolume then
			SoundService.Volume = cache.SoundVolume
		end
	
		cache = {}
		stopOptimizer()
	end
	
	-- ==============================
	-- BOTÃO
	-- ==============================
	
	button.MouseButton1Click:Connect(function()
		if potatoMode then
			restoreAll()
			potatoMode = false
			button.Text = ""
		else
			cache = {}
			disableVisualEffects()
			disableParticles()
			disableMaterialsAndTextures()
			disableSounds()
			reduceRendering()
			startOptimizer()
	
			potatoMode = true
			button.Text = ""
		end
	end)
	
end;
task.spawn(C_69);
-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Fps.FPSDisplay.LocalScript
local function C_6d()
local script = G2L["6d"];
	local waitTime = 0.3
	
	local lastUpdateTime = tick()
	
	local deltaTimesInterval = {}
	
	local numDP = 1
	
	game:GetService("RunService").RenderStepped:Connect(function(deltaTime)
	
		local now = tick()
		local timePassed = now - lastUpdateTime
	
		table.insert(deltaTimesInterval, deltaTime)
	
		if timePassed >= waitTime then
	
			local totalDeltaTime = 0		
			for _, deltaTimeRecorded in pairs(deltaTimesInterval) do
				totalDeltaTime += deltaTimeRecorded
			end
	
			local numDeltas = #deltaTimesInterval
	
			local avgDeltaTime = totalDeltaTime / numDeltas
	
			local framesPerSecond = 1 / avgDeltaTime
			local formattedFPS = string.format("%." .. numDP .. "f", framesPerSecond)
	
			table.clear(deltaTimesInterval)
	
			script.Parent.Text = " " .. formattedFPS
	
			lastUpdateTime = now
		end
	end)
end;
task.spawn(C_6d);
-- StarterGui.Pedrinhuu Menu PVP.PedrinhuuMenu.Outers.Pedrinhuu On Top.LocalScript
local function C_73()
local script = G2L["73"];
	local textLabel = script.Parent
	local RunService = game:GetService("RunService")
	
	local speed = 5 -- velocidade da mudança de cor
	
	RunService.RenderStepped:Connect(function()
		local t = tick() * speed
	
		local r = math.sin(t) * 127 + 128
		local g = math.sin(t + 2) * 127 + 128
		local b = math.sin(t + 4) * 127 + 128
	
		textLabel.TextColor3 = Color3.fromRGB(r, g, b)
	end)
	
end;
task.spawn(C_73);

return G2L["1"], require;

print ("Pedrinhuu On Top")
