local esp_enabled = false
local team_check_enabled = false

function onKeyPress(key)
    if key == 'y' or key == 'Y' then
        esp_enabled = not esp_enabled
        team_check_enabled = not team_check_enabled
        if esp_enabled then
            print("ESP Ativado!")
        else
            print("ESP Desativado!")
        end
        if team_check_enabled then
            print("Team Check Ativado!")
        else
            print("Team Check Desativado!")
        end
    end
end
