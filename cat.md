# 猫のプログラムの作り方(How to develop a cat program)

## 1. プログラムの作り方(How to develop a program)

### 1-1. 完成イメージ(Completed image)

![Cat](figure/cat/cat_talk_program_completed.png)

### 1-2. 作り方(How to develop)

- ![Common](figure/common/make_block_button.png)を押してください。

    Press ![Common](figure/common/make_block_button.png).

- ![Common](figure/common/building_block_button.png)を押してください。

    Press ![Common](figure/common/building_block_button.png).

- 以下の画面が表示されるので、 **『ブロック名』を『猫の会話』に変更** してください。

    When the following screen is displayed, change the "Block Name" to "Cat Conversation" and press the OK button.

![Common](figure/common/init_screen.png)

- 『引数を追加(数値またはテキスト)』をクリックし、 **『number or text』を『猫のセリフ』に変更** 後、OKボタンを押してください。

    Click "Add argument (number or text)", change "number or text" to "Cat's line", and then click OK.

![Cat](figure/cat/init_screen_add_param.png)

- 以下の画面が表示されることを確認してください。

    Confirm that the following screen is displayed.

![Cat](figure/cat/cat_talk_definition.png)

- 以下のブロックを画面中央にドラック＆ドロップします。

    Drag and drop the following blocks to the center of the screen.

![Common](figure/common/costume_button.png) ![Common](figure/common/costume_next.png)

![Common](figure/common/control_button.png) ![Common](figure/common/wait_sec.png)×2 ![Common](figure/common/time_loop.png)

![Common](figure/common/tspeech_button.png) ![Common](figure/common/speech.png)

![Common](figure/common/trans_button.png) ![Common](figure/common/trans.png)

- ![Common](figure/common/wait_sec.png)の数字を **0.1と0.5に変更** します。(数字をダブルクリックすることで、数字を編集できる状態になります。)

    Change the number ![Common](figure/common/wait_sec.png) to 0.1 and 0.5.(Double-clicking on a number, you will be able to edit the number.)

![Cat](figure/cat/wait_sec_set.png)

- ![Common](figure/common/time_loop.png)の数字を **2に変更** します。(数字をダブルクリックすることで、数字を編集できる状態になります。)

    Change the number ![Common](figure/common/time_loop.png) to 2. (Double-clicking on a number, you will be able to edit the number.)

![Cat](figure/cat/time_loop_change.png)

- ![Common](figure/common/trans.png)の **『こんにちわ』** に![Cat](figure/cat/cat_line_param.png)をドラッグ＆ドロップしてください。

    Drag and drop the ![Cat](figure/cat/cat_line_param.png) into "Hello" in ![Common](figure/common/trans.png).

![Cat](figure/cat/set_cat_line.png)

- ![Cat](figure/cat/set_cat_line_small.png)の▼ボタンを押し、表示される言語の一覧から **『英語』を選んでください** 。

    Press the ▼ button on ![Cat](figure/cat/set_cat_line_small.png)A and select "English" from the list of languages displayed.

![Cat](figure/cat/set_cat_line_english.png)

- ![Common](figure/common/speech.png)の『hello』に![Cat](figure/cat/set_cat_line_english_small.png)をドラッグ＆ドロップしてください。

    Drag and drop ![Cat](figure/cat/set_cat_line_english_small.png) to "hello" in ![Common](figure/common/speech.png).

![Cat](figure/cat/speech_connect_trans.png)

- ブロックをくっつけてください。

    Connect the blocks.

![Cat](figure/cat/cat_talk_program.png)

- ![Common](figure/common/variable_button.png)を押してください。

    Press ![Common](figure/common/variable_button.png).

- ![Common](figure/common/list_button.png)を押してください。

    Press ![Common](figure/common/list_button.png).

- **『新しいリスト名：』に『猫とダンサーの会話』と入力** し、OKボタンを押してください。

    Enter "Cat and Dancer's Conversation" in the "New List Name:" field and press the OK button.

- リストが画面上に表示されることを確認してください。

![Cat](figure/cat/blank_list.png)

- リストの＋ボタンを押し、 **『踊って』と『いいよ』を設定** してください。

Press the + button on the list and set the "Dancing" and "OK" settings.

![Cat](figure/cat/cat_dancer_conversation_list.png)

- 以下のブロックを画面中央にドラック＆ドロップします。

    Drag and drop the following blocks to the center of the screen.

![Common](figure/common/event_button.png) ![Common](figure/common/flag.png) ![Common](figure/common/message.png)

![Common](figure/common/variable_button.png) ![Cat](figure/cat/cat_dancer_conversation_list_hidden.png) ![Common](figure/common/cat_dancer_conversation.png)

![Common](figure/common/make_block_button.png) ![Cat](figure/cat/cat_talk_block.png)

![Common](figure/common/tspeech_button.png) ![Common](figure/common/voice.png)

- ![Common](figure/common/cat_dancer_conversation.png)を![Cat](figure/cat/cat_talk_block.png)にドラッグ＆ドロップしてください。

    Drag and drop ![Common](figure/common/cat_dancer_conversation.png) to ![Cat](figure/cat/cat_talk_block.png).

![Cat](figure/cat/cat_dancer_conversation_set.png)

- ブロックをくっつけてください。これでプログラムは完成です。

    Connect the blocks.The program is complete.

Connect the blocks.

![Cat](figure/cat/cat_talk_program_main.png)

- 最後に、プログラムを保存してください。

    Finally, save the program.

![Common](figure/common/save.png)
