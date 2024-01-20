# Swarm Data Analysis Report

> Swarm is a social application from 4Sq that relies on check-in. Users can check in and send photos to their friends at locations they are interested in.
>
> This dataset provides check-in data and personal information data of corresponding check-in users within three city ranges, namely New York City (nyc), San Francisco (sfo), and Hong Kong (hk).
>
> The check-in data for each city includes 8 fields: user ID, local/out of town, check-in location ID, location type, location type ID, location longitude and latitude, and check-in time.
>
> The user data corresponding to check-in in each city includes 6 fields: user ID, local/out of town, male/female, number of check-in posts, number of photo posts, and number of friends.
>
> As is well known, location information has enormous commercial value. This article only provides some preliminary organization and observation.

**Lognormal distribution of clock-in**

![](./SwarmTex/qq.png)

**Factor Model of User Preferences**

![](./SwarmTex/fac2_oblique.png)

![](./SwarmTex/group.png)

**Distinguishing between local and foreign**

![](./SwarmTex/disc.png)

![](./SwarmTex/err_f.png)

---

Dowload：

{download}`Original Data <./SwarmData.zip>`

{download}`(Nearly)Complete Report<./Swarm.pdf>`

{download}`Original Code <./SwarmMatlab.zip>`（*MATLAB*，including realtime scripts, functions and the snapshot of workspace. A bit large.）