2021/9/29 https://www.youtube.com/watch?v=YTzYouYr67Q

### 猜數字小遊戲
- import random
- rang1 = int(input("請設定本局遊戲的最小值:"))
- rang2 = int(input("請設定本局遊戲的最大值:"))
- num = random.randint(rang1,rang2)
- guess = "guess"
- print("數字猜謎遊戲！")
- i = 0
- while guess != num:
-    i += 1
-   guess = int(input("請輸入你猜的數字："))
-
-   if guess == num:
-       print("恭喜，你猜對了！")
-  elif guess < num:
-        print("你猜的數小了...")
-   else:
-        print("你猜的數大了...")
-
- print("你總共猜了%d" %i + "次",end = '')
- print(",快和你朋友較量一下...")
-
![image](https://user-images.githubusercontent.com/43431948/141067109-24f815b5-eb4d-406e-af6e-894468effeae.png)

{
  "nbformat": 4,
  "nbformat_minor": 0,
  "metadata": {
    "colab": {
      "name": "Untitled10.ipynb",
      "provenance": [],
      "authorship_tag": "ABX9TyNTFopn7bArK/Aob4E0xPN9",
      "include_colab_link": true
    },
    "kernelspec": {
      "name": "python3",
      "display_name": "Python 3"
    },
    "language_info": {
      "name": "python"
    }
  },
  "cells": [
    {
      "cell_type": "markdown",
      "metadata": {
        "id": "view-in-github",
        "colab_type": "text"
      },
      "source": [
        "<a href=\"https://colab.research.google.com/github/4070E001-le/S107000660-/blob/main/Email%20%E5%9F%9F%E5%90%8D%E5%88%A4%E6%96%B7%E5%99%A8%E7%A8%8B%E5%BC%8F%E7%A2%BC.ipynb\" target=\"_parent\"><img src=\"https://colab.research.google.com/assets/colab-badge.svg\" alt=\"Open In Colab\"/></a>"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": null,
      "metadata": {
        "id": "NpJOMIDwa9lQ"
      },
      "outputs": [],
      "source": [
        "email = input(\"What is your email address?: \").strip()\n",
        "\n",
        "\n",
        "user_name = email[:email.index(\"@\")]\n",
        "\n",
        "\n",
        "domain_name = email[email.index(\"@\")+1:]\n",
        "\n",
        "\n",
        "output = \"Your username is '{}' and your domain name is '{}'\".format(user_name,domain_name)\n",
        "\n",
        "\n",
        "print(output)"
      ]
    }
  ]
}
