基本的な2048のコードとAIは下記URL及びコメントのコードを参照しました。
https://qiita.com/masa_ramen/items/b497e547a1298a905a2e

それを元にpazzle.pyを作成し、
AI部分はdqn_agent.pyとで分け、
実働部分は両方をimportしてsolve.pyで作動させます。

seleniumの使用に関して、
サンプルコード通りgeckodriverで動きますが、
chromedriverもあり環境によっては動かせるかもしれません。
実作業としてのコード記述は作業.txtに記述しています。

※動作させるにはseleniumの他tensorflow/kerasもpip installしてください。



Basic 2048 codes and AI referenced the following URL and comment code.
https://qiita.com/masa_ramen/items/b497e547a1298a905a2e

Based on that, create pazzle.py,
The AI part is divided with dqn_agent.py,
The working part imports both and works with solve.py.

Regarding the use of selenium,
It moves with geckodriver as sample code,
There is a chromedriver, and it may be able to move depending on the environment.
Code description as actual work is described in work .txt.

* Please also pip install selenium and other tensorflow / keras to make it operate.

