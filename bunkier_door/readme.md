    local success = exports['bunkier_door']:StartBunkierDoor()
    if success then
        ESX.ShowNotification('Udane')
    elseif not success then
        ESX.ShowNotification('Nie Udane')
    end