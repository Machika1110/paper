# Germanium oxide まとめ
## Epitaxial growth of magnetron sputtered NiAl on Ge mediated by native GeOx
URL : https://iopscience.iop.org/article/10.1088/1361-6463/ad164b/meta?casa_token=CdzhVYj2-pkAAAAA:isXwWli6gAqR5Cyte6_Zn4w9vqsx7jnj1utQzpZPtZUBUexnCYw4J6wZZMxuny0bDE3e6NvuInH0e3NzhUNn45ydbyNv_A 

- **Ge基板上にNiAl30nmをエピタキシャル成長で成膜、温度は200~400℃で、Ge酸化物の存在効果も検証**
  - 金属薄膜の成膜は、従来はMBE(Molecular beam epitaxy)だが、成長速度が遅くスケーリングが困難なのでエピタキシャル成長を採用

- NiAlは、立方CsCl型構造（a = 2.88 A）であり、格子定数のミスマッチが小さい。
  - Si(001)上に001方向で蒸着される。
    - Siとの格子定数のミスマッチは -6%
    - Geとの格子定数のミスマッチは 2%
  - Geのオキサイドは超高真空下で熱分解（390~425℃）されることがメリット
    - SiO2はフッ化水素酸などを用い除去する必要がある（1200℃）

- 実験
  - 300nm Si(001)ウェハー上にGeを 1μm の厚さでCVDを用いて蒸着。
  - 蒸着後、H2下で850℃でアニールし、CMPを行い700nmまで研磨し、滑らかな表面を得た。
  - native GeOx はGeが空気に触れることで形成された。
  - NiAlの蒸着を以下の条件で行った。
    - EC7800を使用し、**200℃~400℃で30nmの厚さ** になるまで
    - スパッタガスはArで、使用圧力は0.1Paのオーダー
    - Arの平均自由行程は数センチメートル
  - GeOxの除去を行う場合は、超高真空下で600℃で20分のアニール
    - 600℃は確実に除去を行うため
  - Sampleの対応関係は以下の通り
  
  |Sample番号|NiAl蒸着温度|GeOxの有無|
  |:-:|:-:|:-:|
  |1|200|無し|
  |2|200|有り|
  |3|400|無し|
  |4|400|有り|

  - Follow-upの実験とし、Sample4のNiAl層をCMPで除去し、Germanideを残した

- 結果
  - NiAlの蒸着温度が高いと表面がより粗く（2~10倍）
    - Sample4では10nmほどの穴ができた
    - Sample3は凸凹が大きかった
  - 2θ-θ-scanのピークについては
    - 全体的にNiAl(001)、NiAl(110)、NiAl(002)、Ge(004)、Si(004)
      - Sample4ではNiAl(001)のピークがより大きく出た
      - Sample2ではNiAl(001)のピークが一切出なかった
  - 界面構造
    - Sample2では、1nmのGeOxが見られた
    - Sample4では、Ge/NiAl界面におけるアモルファス酸化物がゲルマニウムの結晶粒界によってとぎれとぎれになっている
      - GermanideとGeOxが共存している
    - Germanideの厚さの 5.8 nm 

- ディスカッション
  - Sample2
    - エピタキシャル成長は確認されず
    - アモルファスGeOxが、NiAlがエピタキシャル成長しGeと接触するのを妨げていた
  - Sample1
    - NiAl(001)のピークが3、4と比べ弱い
    - 蒸着温度による違い
  - Sample3 
    - エピタキシャル成長起きた
  - Sample4では 
    - エピタキシャル成長がGe上で起きた
    - "the presence of GeOx promoted epitaxial growth."
    - GeOxは部分的拡散障壁として機能し、Germanideの形成を可能に
      - GeはGeOxを乗り越えてNiAlへ到達する必要がある
        - 濃度は3%ほど（NiAl中のGeの溶解限界に近いらしい）
        - 余ったGeはNiAl表面上へ移動
      - "The exact mechanism for this difference in diffusion is unknown. 
      However, a possible mechanism could be that the O in native GeOx preferentially oxidizes Al over Ni. 
      This way, Ni is less captured at the GeOx and allowed to diffuse more, compared to Al."
  - 仮説：CaF2型のGermanide/Silicideが"bridge"としてエピタキシャル成長が
    - NiAl/SiでSilicide(CaF2型)が形成された件と同様に、
      - Ni-Al-Ge混合系のCaF2型構造が検知された（τ3型）
      - Ni-Geの化合物は無し
  - Bulk τ3の組成は、Ni34.7Al24.8Ge40.5 ~ Ni35.0Al26.8Ge38.2
    - ネイティブなGeOxの役割は、Niが通過してエピタキシャルτ3が形成される一方で、
      Ge層内のAl濃度を低減することにある可能性がある？
  - native GeOx内の空孔は、
    - NiAlの蒸着中に、熱分解することで発生（400℃なので部分的に分解される）
      - 完全に分解されるのは超高真空下で390~425℃
    - Sample2では空孔が形成されていない
    - Sample4では、GeOx中の隙間は、NiAlの堆積により分解が防がれた。
      - ある論文では、最初に脱離が起き、隙間が横方向に成長した。
  - 低抵抗である点から、NiAlは次世代の配線材料になりうる

- 結論
  - 蒸着温度と、native GeOxの存在の有無という2つのパラメータから実験を行った。
  - Sample4でのみ、膜が均一な方向に成長した。
    - NiAl(001)//Ge(001)およびNiAl(011)//Ge(011)
    - 他のサンプルでは結晶は一部、または全く見られなかった
  - NiAlはGeOxの局所的な隙間を介してGeと接触してエピタキシャル成長したと考えられる
    - 隙間はNiAlの蒸着前に発生した可能性がある
