#!name=机场
#!desc=机场流量

[Script]
Sub_info = script-name=Sub_info,update-interval=3600

Sub_info2 = script-name=Sub_info2,update-interval=3600

Sub_info = type=generic,timeout=10,script-path=https://raw.githubusercontent.com/Rabbit-Spec/Surge/Master/Module/Panel/Sub-info/Moore/Sub-info.js,script-update-interval=0,argument=url=https%3A%2F%2Fsub1.sntp.dev%2FbaseStr%3Ftoken%3D101e1df9fc3cb071e7da5e8d4def1c8b&reset_day=1&title=守候网络&icon=personalhotspot.circle.fill&color=#3CB371

Sub_info2 = type=generic,timeout=10,script-path=https://raw.githubusercontent.com/Rabbit-Spec/Surge/Master/Module/Panel/Sub-info/Moore/Sub-info.js,script-update-interval=0,argument=url=https%3A%2F%2Flogin.yfjc.xyz%2Fapi%2Fv1%2Fclient%2Fsubscribe%3Ftoken%3Ddc0cbd25891815f5a0bb64ec7c6dc7fe&reset_day=1&title=一分机场&icon=camera.macro.circle.fill=#3CB371

[Panel]
Sub_info = script-name=Sub_info,update-interval=86400

Sub_info2 = script-name=Sub_info2,update-interval=86400
