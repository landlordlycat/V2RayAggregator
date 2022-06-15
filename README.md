# TopFreeProxies
[![GitHub Workflow Status](https://img.shields.io/github/workflow/status/alanbobs999/topfreeproxies/sub_merge?label=sub_merge)](https://github.com/alanbobs999/TopFreeProxies/actions/workflows/sub_merge.yml) 

![Watchers](https://img.shields.io/github/watchers/alanbobs999/topfreeproxies) ![Stars](https://img.shields.io/github/stars/alanbobs999/topfreeproxies) ![Forks](https://img.shields.io/github/forks/alanbobs999/topfreeproxies) ![Vistors](https://visitor-badge.laobi.icu/badge?page_id=alanbobs999.topfreeproxies) ![LICENSE](https://img.shields.io/badge/license-CC%20BY--SA%204.0-green.svg)

[仓库介绍](https://github.com/alanbobs999/TopFreeProxies#仓库介绍) | [使用方法](https://github.com/alanbobs999/TopFreeProxies#使用方法) | [节点信息](https://github.com/alanbobs999/TopFreeProxies#节点信息) | [软件推荐](https://github.com/alanbobs999/TopFreeProxies#客户端选择) | [机场推荐](https://github.com/alanbobs999/TopFreeProxies#机场推荐) | [仓库声明](https://github.com/alanbobs999/TopFreeProxies#仓库声明)

## 仓库介绍
本仓库自动化功能全部基于 `GitHub Actions` 实现，如果有需要可以自行 Fork 实现个性化需求。

对网络上各免费节点池及博主分享的节点进行测速筛选出较为稳定高速的节点，再导入到仓库中进行分享记录。所筛选的节点链接在仓库 `./sub/sub_list.json` 文件中，其中大部分为其他 `GitHub` 仓库链接，如果大家有好的订阅链接欢迎提交 PR ，这些链接包含的所有节点会合并在仓库 `./sub/sub_merge.txt` 中。

测速筛选后的节点订阅文件在仓库根目录 `Eterniy`(Base64) 和 `Eternity.yml`(Clash)。同时在仓库的 `./update` 中保留了原始节点链接的的记录。

测速功能使用 [LiteSpeedTest](https://github.com/xxf098/LiteSpeedTest) 在 `GitHub Actions` 环境下实现，所以美国节点较多，不能很好代表国内网络环境下节点可用性，目前正在解决这一问题。

虽然是测速筛选过后的节点，但仍然会出现部分节点不可用的情况，遇到这种情况建议选择`Clash`, `Shadowrocket`之类能自动切换低延迟节点的客户端。

## 使用方法
将以下订阅链接导入相应客户端即可。链接中大部分为 SS 协议节点，少量 Vmess, Trojan ,SSR 协议节点，建议选择协议支持完整的客户端。

- [多协议Base64编码](https://raw.githubusercontent.com/alanbobs999/TopFreeProxies/master/Eternity)
- [Clash](https://raw.githubusercontent.com/alanbobs999/TopFreeProxies/master/Eternity.yml)

另有国内加速链接：

- [多协议Base64编码](https://fastly.jsdelivr.net/gh/alanbobs999/TopFreeProxies@master/Eternity)
- [Clash](https://fastly.jsdelivr.net/gh/alanbobs999/TopFreeProxies@master/Eternity.yml)

>`Clash`链接所使用的配置在仓库`./update/provider/`中，有相应配置文件和以国家分类的`proxy-provider`。
>
>需要其它配置可使用订阅转换工具自行转换。
>自用在线订阅转换网址：[sub-web-modify](https://sub.v1.mk/)

## 节点信息
### 高速节点
高速节点数量: `99`
<details>
  <summary>展开复制节点</summary>

    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9XzA2MTQ2NjAiLCJhZGQiOiJpZXNlaTFlaS5jb20iLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6ImFiYTUwZGQ0LTU0ODQtM2IwNS1iMTRhLTQ2NjFjYWY4NjJkNSIsImFpZCI6IjQiLCJuZXQiOiJ3cyIsInBhdGgiOiIvd3MiLCJob3N0IjoiaWVzZWkxZWkuY29tIiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9XzA2MTU2NTEiLCJhZGQiOiJ1c2Etd2FzaGluZ3Rvbi5sdnVmdC5jb20iLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6ImFiYTUwZGQ0LTU0ODQtM2IwNS1iMTRhLTQ2NjFjYWY4NjJkNSIsImFpZCI6IjQiLCJuZXQiOiJ3cyIsInBhdGgiOiIvd3MiLCJob3N0IjoidXNhLXdhc2hpbmd0b24ubHZ1ZnQuY29tIiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9XzA2MTQ2NjAiLCJhZGQiOiJpZXNlaTFlaS5jb20iLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6ImFiYTUwZGQ0LTU0ODQtM2IwNS1iMTRhLTQ2NjFjYWY4NjJkNSIsImFpZCI6IjQiLCJuZXQiOiJ3cyIsInBhdGgiOiIvd3MiLCJob3N0IjoiaWVzZWkxZWkuY29tIiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9XzA2MTQ2NjAiLCJhZGQiOiJpZXNlaTFlaS5jb20iLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6ImFiYTUwZGQ0LTU0ODQtM2IwNS1iMTRhLTQ2NjFjYWY4NjJkNSIsImFpZCI6IjQiLCJuZXQiOiJ3cyIsInBhdGgiOiIvd3MiLCJob3N0IjoiaWVzZWkxZWkuY29tIiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9XzA2MTU2NTMiLCJhZGQiOiJpZXNlaTFlaS5jb20iLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6ImFiYTUwZGQ0LTU0ODQtM2IwNS1iMTRhLTQ2NjFjYWY4NjJkNSIsImFpZCI6IjQiLCJuZXQiOiJ3cyIsInBhdGgiOiIvd3MiLCJob3N0IjoiaWVzZWkxZWkuY29tIiwidGxzIjoidGxzIn0=
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpHIXlCd1BXSDNWYW8@5.181.234.254:809#US_236
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9XzA2MTU2NTYiLCJhZGQiOiIyMDguOTguNDguMiIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiYWJhNTBkZDQtNTQ4NC0zYjA1LWIxNGEtNDY2MWNhZjg2MmQ1IiwiYWlkIjoiNCIsIm5ldCI6IndzIiwicGF0aCI6Ii93cyIsImhvc3QiOiJpZXNlaTFlaS5jb20iLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDA1MSIsImFkZCI6IjQ1LjM1Ljg0LjE2MiIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiYWJhNTBkZDQtNTQ4NC0zYjA1LWIxNGEtNDY2MWNhZjg2MmQ1IiwiYWlkIjoiNCIsIm5ldCI6IndzIiwicGF0aCI6Ii93cyIsImhvc3QiOiJ1c2EtZGFsbGFzLmx2dWZ0LmNvbSIsInRscyI6InRscyJ9
    trojan://48ac743a-2d49-4191-b804-0c7fa7e01146@mc.vpshax.ml:443?allowInsecure=0#%F0%9F%87%BA%F0%9F%87%B8%20v2rayfree.eu.org%20-%20%E7%BE%8E%E5%9B%BD%E5%8A%A0%E5%88%A9%E7%A6%8F%E5%B0%BC%E4%BA%9A%E5%B7%9E%E6%B4%9B%E6%9D%89%E7%9F%B6MULTACOM%E6%95%B0%E6%8D%AE%E4%B8%AD%E5%BF%83%2018
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HqvCfh7og5qyn5rSyKOayueeuoTrnoLTop6PotYTmupDlkJsyLjApIiwiYWRkIjoiNDUuMzUuODQuMTYyIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiJhYmE1MGRkNC01NDg0LTNiMDUtYjE0YS00NjYxY2FmODYyZDUiLCJhaWQiOiI0IiwibmV0Ijoid3MiLCJwYXRoIjoiL3dzIiwiaG9zdCI6InVzYS1kYWxsYXMubHZ1ZnQuY29tIiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDA1MCIsImFkZCI6IjQ1LjM1Ljg0LjE2MiIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiYWJhNTBkZDQtNTQ4NC0zYjA1LWIxNGEtNDY2MWNhZjg2MmQ1IiwiYWlkIjoiNCIsIm5ldCI6IndzIiwicGF0aCI6Ii93cyIsImhvc3QiOiJ1c2EtZGFsbGFzLmx2dWZ0LmNvbSIsInRscyI6InRscyJ9
    trojan://05742120-ce23-4cc8-88f5-6d221ce45bf4@fhcarm1.gaox.ml:443?allowInsecure=1#38
    trojan://48ac743a-2d49-4191-b804-0c7fa7e01146@mc.vpshax.ml:443?allowInsecure=1#40
    trojan://e3289141-7d98-3831-9fb6-25ed4f7b3b6d@129.146.246.115:8443?allowInsecure=1&sni=v2-px-000.xiaoxiaobujidao.xyz#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD%20025
    trojan://e3289141-7d98-3831-9fb6-25ed4f7b3b6d@129.146.246.115:8443?allowInsecure=1&sni=v2-px-000.xiaoxiaobujidao.xyz#73
    trojan://f39bd244-f5fe-415c-8b98-a1e5250bf178@fhcarm2.gaox.ml:443?allowInsecure=1#%F0%9F%87%AF%F0%9F%87%B5%20%E7%BE%8E%E5%9B%BD%28nodefree.org%E5%85%8D%E8%B4%B9%E8%8A%82%E7%82%B9%E6%97%A5%E6%9B%B4%29_2
    trojan://e3289141-7d98-3831-9fb6-25ed4f7b3b6d@129.146.246.115:8443?allowInsecure=1#%F0%9F%87%BA%F0%9F%87%B8%20US%20309
    trojan://e3289141-7d98-3831-9fb6-25ed4f7b3b6d@129.146.246.115:8443?allowInsecure=1#%F0%9F%87%BA%F0%9F%87%B8%20US%20139
    trojan://e3289141-7d98-3831-9fb6-25ed4f7b3b6d@129.146.246.115:8443?allowInsecure=1&sni=v2-px-000.xiaoxiaobujidao.xyz#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD%20087
    trojan://f39bd244-f5fe-415c-8b98-a1e5250bf178@fhcarm2.gaox.ml:443?allowInsecure=1#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD%28%E7%BB%BF%E5%A4%B4%E5%A4%96%E7%BD%91%E9%9B%86%E5%9B%A2%29%28Public%29
    trojan://f39bd244-f5fe-415c-8b98-a1e5250bf178@fhcarm2.gaox.ml:443?allowInsecure=1#%F0%9F%87%AF%F0%9F%87%B5%20%E7%BE%8E%E5%9B%BD%28nodefree.org%E5%85%8D%E8%B4%B9%E8%8A%82%E7%82%B9%E6%97%A5%E6%9B%B4%29_2
    trojan://e3289141-7d98-3831-9fb6-25ed4f7b3b6d@129.146.246.115:8443?allowInsecure=1&sni=v2-px-000.xiaoxiaobujidao.xyz#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD%20025
    trojan://e3289141-7d98-3831-9fb6-25ed4f7b3b6d@129.146.246.115:8443?allowInsecure=1#56
    trojan://f39bd244-f5fe-415c-8b98-a1e5250bf178@fhcarm2.gaox.ml:443?allowInsecure=1#%F0%9F%87%AF%F0%9F%87%B5%20%E7%BE%8E%E5%9B%BD%28nodefree.org%E5%85%8D%E8%B4%B9%E8%8A%82%E7%82%B9%E6%97%A5%E6%9B%B4%29_2
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9XzA2MTI2MTgiLCJhZGQiOiIxNDMuMTk4LjEzMC4yMSIsInBvcnQiOiI0MjM4MiIsInR5cGUiOiJub25lIiwiaWQiOiIwM2I0NTJhNy05MDdiLTRmNzctOGNhNC02MDI1MGNjODM1YmMiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii8iLCJob3N0IjoiMTQzLjE5OC4xMzAuMjEiLCJ0bHMiOiIifQ==
    ss://YWVzLTI1Ni1jZmI6Yndoc2tyc2tyMDU@172.96.192.100:246#%F0%9F%87%BA%F0%9F%87%B8%20github.com%2Ffreefq%20-%20%E7%BE%8E%E5%9B%BD%E5%8A%A0%E5%88%A9%E7%A6%8F%E5%B0%BC%E4%BA%9A%E5%B7%9E%E6%B4%9B%E6%9D%89%E7%9F%B6IT7%E7%BD%91%E7%BB%9C%201
    trojan://f39bd244-f5fe-415c-8b98-a1e5250bf178@fhcarm2.gaox.ml:443?allowInsecure=1#%F0%9F%87%BA%F0%9F%87%B8%20US%2091
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDA1MCIsImFkZCI6InVzYS13YXNoaW5ndG9uLmx2dWZ0LmNvbSIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiYWJhNTBkZDQtNTQ4NC0zYjA1LWIxNGEtNDY2MWNhZjg2MmQ1IiwiYWlkIjoiNCIsIm5ldCI6IndzIiwicGF0aCI6Ii93cyIsImhvc3QiOiJ1c2Etd2FzaGluZ3Rvbi5sdnVmdC5jb20iLCJ0bHMiOiJ0bHMifQ==
    ss://YWVzLTI1Ni1jZmI6Yndoc2tyc2tyMDM@97.64.31.80:247#US_1184
    trojan://e3289141-7d98-3831-9fb6-25ed4f7b3b6d@129.146.246.115:8443?allowInsecure=1#50
    trojan://e3289141-7d98-3831-9fb6-25ed4f7b3b6d@129.146.246.115:8443?allowInsecure=1#79
    trojan://e3289141-7d98-3831-9fb6-25ed4f7b3b6d@129.146.246.115:8443?allowInsecure=1&sni=v2-px-000.xiaoxiaobujidao.xyz#132
    trojan://05742120-ce23-4cc8-88f5-6d221ce45bf4@fhcarm1.gaox.ml:443?allowInsecure=1#%F0%9F%87%BA%F0%9F%87%B8%20US%20310
    trojan://f39bd244-f5fe-415c-8b98-a1e5250bf178@fhcarm2.gaox.ml:443?allowInsecure=1#19
    trojan://f39bd244-f5fe-415c-8b98-a1e5250bf178@fhcarm2.gaox.ml:443?allowInsecure=1#%F0%9F%87%AF%F0%9F%87%B5%20%E7%BE%8E%E5%9B%BD%28nodefree.org%E5%85%8D%E8%B4%B9%E8%8A%82%E7%82%B9%E6%97%A5%E6%9B%B4%29_2
    trojan://e23f408a-012e-4030-8b31-02022031cb50@fhcamd1.gaox.ml:443?allowInsecure=1#6
    trojan://48ac743a-2d49-4191-b804-0c7fa7e01146@mc.vpshax.ml:443?allowInsecure=1&sni=mc.vpshax.ml#4
    trojan://f39bd244-f5fe-415c-8b98-a1e5250bf178@fhcarm2.gaox.ml:443?allowInsecure=1#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD%28%E7%BB%BF%E5%A4%B4%E5%A4%96%E7%BD%91%E9%9B%86%E5%9B%A2%29%28Public%29
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggZ2l0aHViLmNvbS9mcmVlZnEgLSDnvo7lm70gIDQiLCJhZGQiOiIxNDMuMTk4LjEzMC4yMSIsInBvcnQiOiI0MjM4MiIsInR5cGUiOiJub25lIiwiaWQiOiIwM2I0NTJhNy05MDdiLTRmNzctOGNhNC02MDI1MGNjODM1YmMiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii8iLCJob3N0IjoiIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDAwOCIsImFkZCI6IjE0My4xOTguMTMwLjIxIiwicG9ydCI6IjQyMzgyIiwidHlwZSI6Im5vbmUiLCJpZCI6IjAzYjQ1MmE3LTkwN2ItNGY3Ny04Y2E0LTYwMjUwY2M4MzViYyIsImFpZCI6IjAiLCJuZXQiOiJ0Y3AiLCJwYXRoIjoiL3dzIiwiaG9zdCI6IiIsInRscyI6IiJ9
    trojan://dbf9bf9c-2c3f-474a-8031-d4c00666a989@fhcamd2.gaox.ml:443?allowInsecure=1&sni=fhcamd2.gaox.ml#%F0%9F%87%BA%F0%9F%87%B8%20%28Youtube%E6%8A%80%E6%9C%AF%E5%88%86%E4%BA%AB%E5%AE%A4%29%F0%9F%87%BA%F0%9F%87%B8%E7%BE%8E%E5%9B%BD%2039
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggZ2l0aHViLmNvbS9mcmVlZnEgLSDnvo7lm70gIDQiLCJhZGQiOiIxNDMuMTk4LjEzMC4yMSIsInBvcnQiOiI0MjM4MiIsInR5cGUiOiJub25lIiwiaWQiOiIwM2I0NTJhNy05MDdiLTRmNzctOGNhNC02MDI1MGNjODM1YmMiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii8iLCJob3N0IjoiIiwidGxzIjoiIn0=
    trojan://f39bd244-f5fe-415c-8b98-a1e5250bf178@fhcarm2.gaox.ml:443?allowInsecure=1#25
    trojan://05742120-ce23-4cc8-88f5-6d221ce45bf4@fhcarm1.gaox.ml:443?allowInsecure=1&sni=fhcarm1.gaox.ml#69
    ss://YWVzLTI1Ni1jZmI6Yndoc2tyc2tyMDM@104.243.25.95:253#%F0%9F%87%BA%F0%9F%87%B8%20%28Youtube%E6%8A%80%E6%9C%AF%E5%88%86%E4%BA%AB%E5%AE%A4%29%F0%9F%87%BA%F0%9F%87%B8%E7%BE%8E%E5%9B%BD
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggX1VTX+e+juWbvV81IiwiYWRkIjoiMTQzLjE5OC4xMzAuMjEiLCJwb3J0IjoiNDIzODIiLCJ0eXBlIjoibm9uZSIsImlkIjoiMDNiNDUyYTctOTA3Yi00Zjc3LThjYTQtNjAyNTBjYzgzNWJjIiwiYWlkIjoiMCIsIm5ldCI6InRjcCIsInBhdGgiOiIvIiwiaG9zdCI6IiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9XzA2MTUyMjI4IiwiYWRkIjoiMTQzLjE5OC4xMzAuMjEiLCJwb3J0IjoiNDIzODIiLCJ0eXBlIjoibm9uZSIsImlkIjoiMDNiNDUyYTctOTA3Yi00Zjc3LThjYTQtNjAyNTBjYzgzNWJjIiwiYWlkIjoiMCIsIm5ldCI6InRjcCIsInBhdGgiOiIvcXRoYW5nIiwiaG9zdCI6IiIsInRscyI6IiJ9
    trojan://05742120-ce23-4cc8-88f5-6d221ce45bf4@fhcarm1.gaox.ml:443?allowInsecure=1#%F0%9F%87%BA%F0%9F%87%B8%20US%2013
    trojan://05742120-ce23-4cc8-88f5-6d221ce45bf4@fhcarm1.gaox.ml:443?allowInsecure=1#%F0%9F%87%BA%F0%9F%87%B8%20US%20233
    ss://YWVzLTI1Ni1jZmI6Yndoc2tyc2tyMDM@97.64.31.80:247#%F0%9F%87%BA%F0%9F%87%B8%20github.com%2Ffreefq%20-%20%E7%BE%8E%E5%9B%BD%E5%8A%A0%E5%88%A9%E7%A6%8F%E5%B0%BC%E4%BA%9A%E5%B7%9E%E6%B4%9B%E6%9D%89%E7%9F%B6IT7%E7%BD%91%E7%BB%9C%2039
    trojan://05742120-ce23-4cc8-88f5-6d221ce45bf4@fhcarm1.gaox.ml:443?allowInsecure=1#%F0%9F%87%BA%F0%9F%87%B8%20US%20167
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggZ2l0aHViLmNvbS9mcmVlZnEgLSDnvo7lm70gIDQiLCJhZGQiOiIxNDMuMTk4LjEzMC4yMSIsInBvcnQiOiI0MjM4MiIsInR5cGUiOiJub25lIiwiaWQiOiIwM2I0NTJhNy05MDdiLTRmNzctOGNhNC02MDI1MGNjODM1YmMiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii8iLCJob3N0IjoiIiwidGxzIjoiIn0=
    trojan://05742120-ce23-4cc8-88f5-6d221ce45bf4@fhcarm1.gaox.ml:443?allowInsecure=1#63
    ss://YWVzLTI1Ni1jZmI6Yndoc2tyc2tyMDM@97.64.31.80:247#%F0%9F%87%BA%F0%9F%87%B8%20github.com%2Ffreefq%20-%20%E7%BE%8E%E5%9B%BD%E5%8A%A0%E5%88%A9%E7%A6%8F%E5%B0%BC%E4%BA%9A%E5%B7%9E%E6%B4%9B%E6%9D%89%E7%9F%B6IT7%E7%BD%91%E7%BB%9C%2039
    trojan://f39bd244-f5fe-415c-8b98-a1e5250bf178@fhcarm2.gaox.ml:443?allowInsecure=1#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD%28%E7%BB%BF%E5%A4%B4%E5%A4%96%E7%BD%91%E9%9B%86%E5%9B%A2%29%28Public%29
    ss://YWVzLTI1Ni1nY206M2Y0MTFlODctM2U5My00ZjIzLWJjMjItMjYzYTc0OGJjOGM1@164.92.99.255:4649#%F0%9F%87%BA%F0%9F%87%B8%20US%208
    trojan://05742120-ce23-4cc8-88f5-6d221ce45bf4@fhcarm1.gaox.ml:443?allowInsecure=1#36
    trojan://e3289141-7d98-3831-9fb6-25ed4f7b3b6d@129.146.246.115:8443?allowInsecure=1&sni=v2-px-000.xiaoxiaobujidao.xyz#41
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTozZjQxMWU4Ny0zZTkzLTRmMjMtYmMyMi0yNjNhNzQ4YmM4YzU@164.92.107.59:1645#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD11
    ss://YWVzLTI1Ni1jZmI6Yndoc2tyc2tyMDM@172.96.192.58:254#US_262
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDAyMyIsImFkZCI6IjEwNC4xNDkuMTU0LjE1NCIsInBvcnQiOiIyNTk2NiIsInR5cGUiOiJub25lIiwiaWQiOiJjYTA2ZTBmMC1jYTZlLTQxOGYtODAwZC05N2IyM2JhNTFiY2EiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL1ZUZDRvM0tqLyIsImhvc3QiOiIiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9XzA2MTUyMjI5IiwiYWRkIjoiMTQzLjE5OC4xMzAuMjEiLCJwb3J0IjoiNDIzODIiLCJ0eXBlIjoibm9uZSIsImlkIjoiMDNiNDUyYTctOTA3Yi00Zjc3LThjYTQtNjAyNTBjYzgzNWJjIiwiYWlkIjoiMCIsIm5ldCI6InRjcCIsInBhdGgiOiIvY2hhdCIsImhvc3QiOiIiLCJ0bHMiOiIifQ==
    ss://YWVzLTI1Ni1jZmI6Yndoc2tyc2tyMDM@172.96.192.58:254#US_262
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9XzA2MTUwMDEiLCJhZGQiOiIxNDMuMTk4LjEzMC4yMSIsInBvcnQiOiI0MjM4MiIsInR5cGUiOiJub25lIiwiaWQiOiIwM2I0NTJhNy05MDdiLTRmNzctOGNhNC02MDI1MGNjODM1YmMiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii8iLCJob3N0IjoiIiwidGxzIjoiIn0=
    trojan://48ac743a-2d49-4191-b804-0c7fa7e01146@mc.vpshax.ml:443?allowInsecure=0#%E8%BF%99%E4%BA%9B%E8%8A%82%E7%82%B9%E5%8F%AA%E8%83%BD%E5%A4%87%E7%94%A8%E6%88%96%E8%80%85%E9%98%B2%E6%AD%A2%E5%A4%B1%E8%81%94%EF%BC%8C%E8%99%BD%E7%84%B6%E8%B4%A8%E9%87%8F%E5%B9%B6%E4%B8%8D%E6%98%AF%E5%BE%88%E5%A5%BD%EF%BC%8C%E4%B9%9F%E8%AF%B7%E4%BD%8E%E8%B0%83%E4%BD%BF%E7%94%A8%3A%29
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9XzA2MTUyMjMwIiwiYWRkIjoiMTQzLjE5OC4xMzAuMjEiLCJwb3J0IjoiNDIzODIiLCJ0eXBlIjoibm9uZSIsImlkIjoiMDNiNDUyYTctOTA3Yi00Zjc3LThjYTQtNjAyNTBjYzgzNWJjIiwiYWlkIjoiMCIsIm5ldCI6InRjcCIsInBhdGgiOiIvZ28iLCJob3N0IjoiIiwidGxzIjoiIn0=
    trojan://f39bd244-f5fe-415c-8b98-a1e5250bf178@fhcarm2.gaox.ml:443?allowInsecure=1#35
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9XzA2MTUyMjI3IiwiYWRkIjoiMTQzLjE5OC4xMzAuMjEiLCJwb3J0IjoiNDIzODIiLCJ0eXBlIjoibm9uZSIsImlkIjoiMDNiNDUyYTctOTA3Yi00Zjc3LThjYTQtNjAyNTBjYzgzNWJjIiwiYWlkIjoiMCIsIm5ldCI6InRjcCIsInBhdGgiOiIvaW5kZXgiLCJob3N0IjoiIiwidGxzIjoiIn0=
    ss://YWVzLTI1Ni1jZmI6Yndoc2tyc2tyMDM@97.64.31.80:247#%F0%9F%87%BA%F0%9F%87%B8%20v2rayfree.eu.org%20-%20%E7%BE%8E%E5%9B%BD%E5%8A%A0%E5%88%A9%E7%A6%8F%E5%B0%BC%E4%BA%9A%E5%B7%9E%E6%B4%9B%E6%9D%89%E7%9F%B6IT7%E7%BD%91%E7%BB%9C%2039
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9XzA2MTUyMjQyIiwiYWRkIjoiMTQzLjE5OC4xMzAuMjEiLCJwb3J0IjoiNDIzODIiLCJ0eXBlIjoibm9uZSIsImlkIjoiMDNiNDUyYTctOTA3Yi00Zjc3LThjYTQtNjAyNTBjYzgzNWJjIiwiYWlkIjoiMCIsIm5ldCI6InRjcCIsInBhdGgiOiIvIiwiaG9zdCI6InVzZnJlZTIuamlhbnRpYW4ueHl6IiwidGxzIjoiIn0=
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTozZjQxMWU4Ny0zZTkzLTRmMjMtYmMyMi0yNjNhNzQ4YmM4YzU@164.92.115.89:3125#%F0%9F%87%BA%F0%9F%87%B8%20github.com%2Ffreefq%20-%20%E7%BE%8E%E5%9B%BD%20%207
    vmess://eyJ2IjoiMiIsInBzIjoiX+ayueeuoe+8muWFqOe9keacgOW8uueZveWrliIsImFkZCI6IjEwNC4xNDkuMTU0LjE1NCIsInBvcnQiOiIyNTk2NiIsInR5cGUiOiJub25lIiwiaWQiOiJjYTA2ZTBmMC1jYTZlLTQxOGYtODAwZC05N2IyM2JhNTFiY2EiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL1ZUZDRvM0tqLyIsImhvc3QiOiJhd2Vpa2VqaS1Zb3VUdWJlIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9KFRH6aKR6YGTOkBreHN3YSkiLCJhZGQiOiJ1czIuYXNhc2FzLnRvcCIsInBvcnQiOiIxODExNyIsInR5cGUiOiJub25lIiwiaWQiOiI4MGVmYTcxYi1hMTY0LTMwNTctYmRmZC1lZDI4NTIxMjU2ZmUiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL3YycmF5IiwiaG9zdCI6InVzMi5hc2FzYXMudG9wIiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDAzMyIsImFkZCI6IjEwNC4xNDkuMTU0LjE1NCIsInBvcnQiOiIyNTk2NiIsInR5cGUiOiJub25lIiwiaWQiOiJjYTA2ZTBmMC1jYTZlLTQxOGYtODAwZC05N2IyM2JhNTFiY2EiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL1ZUZDRvM0tqLyIsImhvc3QiOiIiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9XzA2MTUyMzA1IiwiYWRkIjoiMTA0LjE0OS4xNTQuMTU0IiwicG9ydCI6IjI1OTY2IiwidHlwZSI6Im5vbmUiLCJpZCI6ImNhMDZlMGYwLWNhNmUtNDE4Zi04MDBkLTk3YjIzYmE1MWJjYSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvVlRkNG8zS2ovIiwiaG9zdCI6InQubWUvbWVuZ2dlODg4ODg4ODgiLCJ0bHMiOiIifQ==
    trojan://dbf9bf9c-2c3f-474a-8031-d4c00666a989@fhcamd2.gaox.ml:443?allowInsecure=1#39
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggVVMt6auY6YCf6IqC54K55o6o6I2Q77yadjEubWsvdmlwIiwiYWRkIjoiMTUwLjIzMC40MS45IiwicG9ydCI6IjIzMjkyIiwidHlwZSI6Im5vbmUiLCJpZCI6Ijk1NmM2YzJmLWJmNTQtNGI4Ny1mYWZkLTRiNzY3Y2ExMjc1MCIsImFpZCI6IjAiLCJuZXQiOiJ0Y3AiLCJwYXRoIjoiLyIsImhvc3QiOiIiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggZ2l0aHViLmNvbS9mcmVlZnEgLSDnvo7lm70gIDI3IiwiYWRkIjoidXNhLXdhc2hpbmd0b24ubHZ1ZnQuY29tIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiJhYmE1MGRkNC01NDg0LTNiMDUtYjE0YS00NjYxY2FmODYyZDUiLCJhaWQiOiI0IiwibmV0Ijoid3MiLCJwYXRoIjoiL3dzIiwiaG9zdCI6InVzYS13YXNoaW5ndG9uLmx2dWZ0LmNvbSIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9XzA2MTUyMjUyIiwiYWRkIjoiMTQzLjE5OC4xMzAuMjEiLCJwb3J0IjoiNDIzODIiLCJ0eXBlIjoibm9uZSIsImlkIjoiMDNiNDUyYTctOTA3Yi00Zjc3LThjYTQtNjAyNTBjYzgzNWJjIiwiYWlkIjoiMCIsIm5ldCI6InRjcCIsInBhdGgiOiIvbGl2ZSIsImhvc3QiOiJjY3R2LmNvbSIsInRscyI6IiJ9
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTozZjQxMWU4Ny0zZTkzLTRmMjMtYmMyMi0yNjNhNzQ4YmM4YzU@164.92.107.59:1645#%F0%9F%87%BA%F0%9F%87%B8%20US%2012
    trojan://dbf9bf9c-2c3f-474a-8031-d4c00666a989@fhcamd2.gaox.ml:443?allowInsecure=1&sni=fhcamd2.gaox.ml#77
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDAxMCIsImFkZCI6IjE1MC4yMzAuNDEuOSIsInBvcnQiOiIyMzI5MiIsInR5cGUiOiJub25lIiwiaWQiOiI5NTZjNmMyZi1iZjU0LTRiODctZmFmZC00Yjc2N2NhMTI3NTAiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii93cyIsImhvc3QiOiIiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9XzA2MTU2NjEiLCJhZGQiOiI2Ny4yMS43Mi40MSIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiMjU2NmQwMGYtMjE4Yy00OGY3LTlhMzYtMTNkM2Q2ZjFhNzI0IiwiYWlkIjoiNjQiLCJuZXQiOiJ3cyIsInBhdGgiOiIvcGF0aC8xNzM0MTgxNDExMjMiLCJob3N0Ijoid3d3LjE3MDgwMTAwLnh5eiIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9XzA2MTQ2NjgiLCJhZGQiOiI2Ny4yMS43Mi40MSIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiMjU2NmQwMGYtMjE4Yy00OGY3LTlhMzYtMTNkM2Q2ZjFhNzI0IiwiYWlkIjoiNjQiLCJuZXQiOiJ3cyIsInBhdGgiOiIvcGF0aC8xNzM0MTgxNDExMjMiLCJob3N0Ijoid3d3LjE3MDgwMTAwLnh5eiIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggZ2l0aHViLmNvbS9mcmVlZnEgLSDnvo7lm70gIDciLCJhZGQiOiIxNTAuMjMwLjQxLjkiLCJwb3J0IjoiMjMyOTIiLCJ0eXBlIjoibm9uZSIsImlkIjoiOTU2YzZjMmYtYmY1NC00Yjg3LWZhZmQtNGI3NjdjYTEyNzUwIiwiYWlkIjoiMCIsIm5ldCI6InRjcCIsInBhdGgiOiIvdERaY0NxYyIsImhvc3QiOiJnY2ZyZWUxLmdhbGF4eS1jbG91ZC5pY3UiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9XzA2MTQxMTAyIiwiYWRkIjoiMTUwLjIzMC40MS45IiwicG9ydCI6IjIzMjkyIiwidHlwZSI6Im5vbmUiLCJpZCI6Ijk1NmM2YzJmLWJmNTQtNGI4Ny1mYWZkLTRiNzY3Y2ExMjc1MCIsImFpZCI6IjAiLCJuZXQiOiJ0Y3AiLCJwYXRoIjoiLyIsImhvc3QiOiIiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9XzA2MTQ2NjgiLCJhZGQiOiI2Ny4yMS43Mi40MSIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiMjU2NmQwMGYtMjE4Yy00OGY3LTlhMzYtMTNkM2Q2ZjFhNzI0IiwiYWlkIjoiNjQiLCJuZXQiOiJ3cyIsInBhdGgiOiIvcGF0aC8xNzM0MTgxNDExMjMiLCJob3N0Ijoid3d3LjE3MDgwMTAwLnh5eiIsInRscyI6InRscyJ9
    trojan://7cb64c49-2ce5-4fa6-9b79-9c02eb54735c@usfree1.jiantian.xyz:23425?allowInsecure=1&sni=usfree1.jiantian.xyz#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD1%E5%85%AC%E7%9B%8A
    trojan://7dafe71e-2be6-302f-bdfc-e6319a3299bc@tj-us01.yiyodns.xyz:443?allowInsecure=0#%F0%9F%87%BA%F0%9F%87%B8%20v2rayfree.eu.org%20-%20%E7%BE%8E%E5%9B%BD%E6%83%A0%E6%99%AEHP%2019
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggZ2l0aHViLmNvbS9mcmVlZnEgLSDnvo7lm73liqDliKnnpo/lsLzkuprlt57mtJvmnYnnn7ZETUlU5pWw5o2u5Lit5b+DIDIwIiwiYWRkIjoidXMyLmFzYXNhcy50b3AiLCJwb3J0IjoiMTgxMTciLCJ0eXBlIjoibm9uZSIsImlkIjoiODBlZmE3MWItYTE2NC0zMDU3LWJkZmQtZWQyODUyMTI1NmZlIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii92MnJheSIsImhvc3QiOiJ1czIuYXNhc2FzLnRvcCIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi6L+Z5Lqb6IqC54K55Y+q6IO95aSH55So5oiW6ICF6Ziy5q2i5aSx6IGU77yM6Jm954S26LSo6YeP5bm25LiN5piv5b6I5aW977yM5Lmf6K+35L2O6LCD5L2/55SoOikiLCJhZGQiOiIxNTUuMjQ4LjIwMi4yMDMiLCJwb3J0IjoiMTQ1NjQiLCJ0eXBlIjoiYXV0byIsImlkIjoiNGEwZGEzNzktYTdjYy00Mzg5LTg4ZDctNDU1MTRiODk2ODgzIiwiYWlkIjoiMCIsIm5ldCI6InRjcCIsInBhdGgiOiIvIiwiaG9zdCI6IjE1NS4yNDguMjAyLjIwMyIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggdjJyYXlmcmVlLmV1Lm9yZyAtIOe+juWbvSAgMyIsImFkZCI6IjE1NS4yNDguMjAyLjIwMyIsInBvcnQiOiIxNDU2NCIsInR5cGUiOiJhdXRvIiwiaWQiOiI0YTBkYTM3OS1hN2NjLTQzODktODhkNy00NTUxNGI4OTY4ODMiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii8iLCJob3N0IjoiIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggWzA2LTE1XXxvc2xvb2t8576O5Zu9KFVTKVVTQS9TYW5Kb3NlXzI0IiwiYWRkIjoiMTU1LjI0OC4yMDIuMjAzIiwicG9ydCI6IjE0NTY0IiwidHlwZSI6Im5vbmUiLCJpZCI6IjRhMGRhMzc5LWE3Y2MtNDM4OS04OGQ3LTQ1NTE0Yjg5Njg4MyIsImFpZCI6IjAiLCJuZXQiOiJ0Y3AiLCJwYXRoIjoiLyIsImhvc3QiOiIiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9XzA2MTU2NjUiLCJhZGQiOiIxNTAuMjMwLjQzLjEwNiIsInBvcnQiOiI1NDgyOSIsInR5cGUiOiJub25lIiwiaWQiOiJmMmI1YzNmZi04NmM3LTRlZmEtODMxZi1mZjBmY2Q3NjU2YTUiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii93cyIsImhvc3QiOiIiLCJ0bHMiOiIifQ==
    trojan://58d32c66-43b1-4561-9951-d87c9123774e@jgwld4.gaox.ml:443?allowInsecure=1#18
    trojan://71b55a84-3fac-4458-abff-eaad79219c91@jgwld3.gaox.ml:443?allowInsecure=1#36
    trojan://71b55a84-3fac-4458-abff-eaad79219c91@jgwld3.gaox.ml:443?allowInsecure=1#%F0%9F%87%AC%F0%9F%87%A7%20%5B06-15%5D%7Coslook%7C%E8%8B%B1%E5%9B%BD%28GB%29United%2BKiongdom%2FSlough_27
    trojan://71b55a84-3fac-4458-abff-eaad79219c91@jgwld3.gaox.ml:443?allowInsecure=1#%F0%9F%87%AC%F0%9F%87%A7%20mattkaydiary.com%7C%E8%8B%B1%E5%9B%BD%28GB%29United%2BKiongdom%2FSlough_27
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpHIXlCd1BXSDNWYW8@78.129.253.9:809#%F0%9F%87%AC%F0%9F%87%A7%20GB%E8%8B%B1%E5%9B%BD%28Youtube%E6%8A%80%E6%9C%AF%E5%88%86%E4%BA%AB%E5%AE%A4%29%2016

</details>

### 所有节点
合并节点总数: `7411`
[节点链接](https://raw.githubusercontent.com/alanbobs999/TopFreeProxies/master/sub/sub_merge.txt)

### 节点来源
- [pojiezhiyuanjun/freev2](https://github.com/pojiezhiyuanjun/freev2), 节点数量: `133`
- [chfchf0306/clash](https://github.com/chfchf0306/clash), 节点数量: `427`
- [xiyaowong/freeFQ](https://github.com/xiyaowong/freeFQ), 节点数量: `163`
- [freefq/free](https://github.com/freefq/free), 节点数量: `79`
- [learnhard-cn/free_proxy_ss](https://github.com/learnhard-cn/free_proxy_ss), 节点数量: `161`
- [vpei/Free-Node-Merge](https://github.com/vpei/Free-Node-Merge), 节点数量: `100`
- [colatiger/v2ray-nodes](https://github.com/colatiger/v2ray-nodes), 节点数量: `75`
- [oslook/clash-freenode](https://github.com/oslook/clash-freenode), 节点数量: `42`
- [ssrsub/ssr](https://github.com/ssrsub/ssr), 节点数量: `279`
- [Leon406/SubCrawler](https://github.com/Leon406/SubCrawler), 节点数量: `3451`
- [yu-steven/openit](https://github.com/yu-steven/openit), 节点数量: `113`
- [iwxf/free-v2ray](https://github.com/iwxf/free-v2ray), 节点数量: `8`
- [gooooooooooooogle/Clash-Config](https://github.com/gooooooooooooogle/Clash-Config), 节点数量: `42`
- [Jsnzkpg/Jsnzkpg](https://github.com/Jsnzkpg/Jsnzkpg), 节点数量: `65`
- [ermaozi/get_subscribe](https://github.com/ermaozi/get_subscribe), 节点数量: `145`
- [wrfree/free](https://github.com/wrfree/free), 节点数量: `79`
- [GreenFishStudio/GreenFish](https://github.com/GreenFishStudio/GreenFish), 节点数量: `56`
- [tomdegnan/clashrule](https://github.com/tomdegnan/clashrule), 节点数量: `214`
- [changfengoss](https://github.com/ronghuaxueleng/get_v2), 节点数量: `39`
- [anaer/Sub](https://github.com/anaer/Sub), 节点数量: `67`
- [xrayfree/free-ssr-ss-v2ray-vpn-clash](https://github.com/xrayfree/free-ssr-ss-v2ray-vpn-clash), 节点数量: `413`
- [mhmhone/shadowrocket-free-subscribe](https://github.com/mhmhone/shadowrocket-free-subscribe), 节点数量: `64`
- [aiboboxx/v2rayfree](https://github.com/aiboboxx/v2rayfree), 节点数量: `80`
- [moneyfly1/sublist](https://github.com/moneyfly1/sublist), 节点数量: `115`
- [poduv/poduv](https://github.com/poduv/poduv), 节点数量: `36`
- [ok1991/v2ray](https://github.com/ok1991/v2ray), 节点数量: `39`
- [parkerpa/jsfxs](https://github.com/parkerpa/jsfxs), 节点数量: `582`
- [Pawdroid/Free-servers](https://github.com/Pawdroid/Free-servers), 节点数量: `144`
- [Nodefree.org](https://github.com/Fukki-Z/nodefree), 节点数量: `101`

## 客户端选择
### 主流桌面客户端
|                            MacOS                             |                            Linux                             |                           Windows                            | 简易描述                                           |
| :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: | :------------------------------------------------- |
| [CFW](https://github.com/Fndroid/clash_for_windows_pkg/releases) | [CFW](https://github.com/Fndroid/clash_for_windows_pkg/releases) | [CFW(Clash For Windows)](https://github.com/Fndroid/clash_for_windows_pkg/releases) | SS, SSR, Trojan, Vmess, VLESS协议支持，策略分流能力强。            |
|     [Qv2ray](https://github.com/Qv2ray/Qv2ray/releases)      |     [Qv2ray](https://github.com/Qv2ray/Qv2ray/releases)      |     [Qv2ray](https://github.com/Qv2ray/Qv2ray/releases)      | SS, SSR, Trojan, Vmess, VLESS, Trojan-Go协议支持（需安装相关插件）。 |
|                              ×                               |                              ×                               |      [V2rayN](https://github.com/2dust/v2rayN/releases)      | SS, Trojan, Vmess, VLESS协议支持，有测速，测延迟功能，支持订阅，二维码，剪贴板导入及手动配置。                 |
|                              ×                               |                              ×                               |    [WinXray](https://github.com/TheMRLL/winxray/releases)    | SS, SSR, Trojan, Vmess, VLESS协议支持，支持自动连接最快节点。            |
|                              ×                               |                              ×                               | [Shadowsocks-windows](https://github.com/shadowsocks/shadowsocks-windows/releases) | SS协议支持， SS 专用客户端。                                       |
|                              ×                               |                              ×                               | [ShadowsocksR-windows](https://github.com/HMBSbige/ShadowsocksR-Windows/releases) | SSR协议支持，SSR 专用客户端。                                      |
|                [Surge](https://nssurge.com/)                 |                              ×                               |                              ×                               | SS, Trojan, Vmess协议支持，著名网络调试工具，策略分流能力强大，需付费。                        |
|   [ClashX](https://github.com/yichengchen/clashX/releases)   |                              ×                               |                              ×                               | SS, SSR, Trojan, Vmess协议支持，占用资源较少。                   |
|      [V2rayU](https://github.com/yanue/V2rayU/releases)      |                              ×                               |                              ×                               | SS, Trojan, Vmess协议支持，支持订阅，二维码，剪贴板导入，手动配置，二维码分享，与 V2RayN 类似。                        |

### 主流移动客户端
|                          iOS/iPadOS                          |                           Android                            | 简易描述                                                     |
| :----------------------------------------------------------: | :----------------------------------------------------------: | ------------------------------------------------------------ |
| [Shadowrocket](https://apps.apple.com/us/app/shadowrocket/id932747118) | [Shadowrocket](https://play.google.com/store/apps/details?id=com.v2cross.proxy) | SS, SSR, Trojan, Vmess, VLESS协议支持，iOS端需在非国区 App Store 购买，美区售价 $2.99；安卓端非与 iOS 端同一作者，不支持 SSR 协议，免费且内置免费节点。 |
|                [Surge](https://nssurge.com/)                 |                              ×                               | SS, Trojan, Vmess协议支持，iOS 端著名网络调试工具，需付费。                                  |
| [Quantumult X](https://apps.apple.com/us/app/quantumult-x/id1443988620) |                              ×                               | SS, SSR, Trojan, Vmess协议支持，需在非国区AppStore购买，美区售价$4.99。 |
| [Potatso Lite](https://apps.apple.com/us/app/potatso-lite/id1239860606) |                              ×                               | SS, SSR协议支持，需在非国区AppStore购买，免费。              |
|                              ×                               | [Surfboard](https://play.google.com/store/apps/details?id=com.getsurfboard) | SS, SSR, Vmess协议支持，安卓端网络调试软件，兼容 Surge 2 配置。 |
|                              ×                               | [CFA(Clash For Android)](https://github.com/Kr328/ClashForAndroid/releases) | SS, SSR, Trojan, Vmess协议支持。                             |
|                              ×                               |  [SagerNet](https://github.com/SagerNet/SagerNet/releases)   | SS, SSR, Trojan, Vmess, VLESS协议支持。                      |
|                              ×                               | [Shadowsocks-android](https://github.com/shadowsocks/shadowsocks-android/releases) | SS协议支持，安卓专用 SS 客户端。                                                 |
|                              ×                               | [ShadowsocksR-android](https://github.com/HMBSbige/ShadowsocksR-Android/releases) | SSR协议支持，安卓专用 SSR 客户端。                                                |
|                              ×                               |     [V2rayNG](https://github.com/2dust/v2rayNG/releases)     | SS, Trojan, Vmess, VLESS协议支持，v2ray 内核。                           |

## 机场推荐
免费节点失效太快，推荐一些性价比高的机场应急使用。
- [魔戒.net](https://www.mojie.cyou/#/register?code=sAbl0qtT)
  - 按量计费机场, 1¥10G, 10¥130G
  - 所有套餐均是一样的节点与一样的服务，所有套餐流量永不过期，用完为止，不限制客户端数量，最高可提供 2Gbps 峰值
- [大迅云](https://daxun.club/#/register?code=JPmAFPav)
  - 最低月付 5¥50G, 12¥200G, 购买 12¥ 及以上套餐免费领取奈飞 + 迪士尼 Plus 共享号
  - 原生IP负载均衡，流媒体解锁晚高峰油管秒开，主打性价比，有试用
- [阿伟云](https://awslcn.xyz/#/register?code=8C18uZwl)
  - 最低月付 1¥ 起, 9.99¥100G
  - 无带宽速率限制，有流媒体解锁，香港 BGP 中继线路

## 仓库声明
订阅节点仅作学习交流使用，只是对网络上节点的优选排序，用于查找资料，学习知识，不做任何违法行为。所有资源均来自互联网，仅供大家交流学习使用，出现违法问题概不负责。

## 星标统计
[![Star History Chart](https://api.star-history.com/svg?repos=alanbobs999/TopFreeProxies&type=Date)](https://star-history.com/#alanbobs999/TopFreeProxies&Date)