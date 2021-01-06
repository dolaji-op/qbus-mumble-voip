
Change DBFW to your core name

Done by Dolaji#1111

Discord - https://discord.gg/qZQfHuYWSm




Open Qb phone client/main.lua and change some lines



Find this line
exports.tokovoip_script:removePlayerFromRadio(PhoneData.CallData.CallId)

replace this line
exports["mumble-voip"]:SetCallChannel(0)




Find this line
exports.tokovoip_script:addPlayerToRadio(PhoneData.CallData.CallId, 'Phone')

replace this line
exports["mumble-voip"]:SetCallChannel(PhoneData.CallData.CallId, 'Phone')




Do not sell this fuckers



