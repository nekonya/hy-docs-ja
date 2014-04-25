==========
Quickstart
==========

.. image:: _static/cuddles-transparent-small.png
   :alt: Karen Rustard's Cuddles

(Thanks to Karen Rustad for Cuddles!)


**手っ取り早くHy環境を取得する方法**:

1. `Python仮想環境
   <https://pypi.python.org/pypi/virtualenv>`_\ を作ませう
2. Python仮想環境を実行しませう
3. コンソールで``pip install hy``と入力することで`PyPI <https://pypi.python.org/pypi/hy>`_\ によるHyのインストールをするです
4. コンソールで``hy``を入力することでREPLを起動するです
5. REPLのプロンプトで以下のように入力しませう::

       => (print "Hy!")
       Hy!
       => (defn salutationsnm [name] (print (+ "Hy " name "!")))
       => (salutationsnm "おまいら")
       Hy おまいら!

       などなど

6. REPLを終了するならばCTRL-Dを入力するですよ

すんばらしい！Hy環境が手に入っちゃったですよ！それじゃあイッチョHyのプログラムを書こうジャマイカ！

7. プログラミング用のエディタを開いて以下を入力するです::

       (print "I was going to code in python syntax, but then I got hy.")

8. ``awesome.hy``\ と保存します
9. そして，あなたの最初のHyプログラムを実行するです::

        hy awesome.hy

10. 過呼吸を起こさないように深く呼吸をしませう

11. 悪人のような笑みを浮かべて秘密の隠れ家にこそこそと引きこもり（初めから引きこもってるならそのままでOK），ここじゃ口にできないようなあんなことこんなことをやらかしちゃいませう！（ママンに怒られないようにな！）
