# ダンサーのプログラムの作り方(How to develop a dancer program)

## 1. プログラムを作る前の準備(Preparation before develop the program)

- ![Common](figure/common/sprite+button.png)ボタンをクリックしてください。

    Click on the ![Common](figure/common/sprite+button.png) button.

- **Champ99** を選択、クリックしてください。

    Select a Champ99 and click on it.

![Dancer](figure/dancer/select_dancer_sprite.png)

- スプライトが設定されていることを確認してください。

    Confirm that the selected sprite is set.

![Dancer](figure/dancer/set_dancer_sprite.png)

## 2. プログラムの作り方(How to develop a program)

### 2-1. 完成イメージ(Completed image)

![Dancer](figure/dancer/dancer_program_completed.png)

### 2-2. 作り方(How to develop)

- ![Common](figure/common/make_block_button.png)を押してください。

    Press ![Common](figure/common/make_block_button.png).

- ![Common](figure/common/building_block_button.png)を押してください。

    Press ![Common](figure/common/building_block_button.png).

- 以下の画面が表示されるので、 **『ブロック名』を『ダンサーの会話』に変更** してください。

    When the following screen is displayed, change the "Block Name" to "Dancer Conversation" and press the OK button.

![Dancer](figure/dancer/init_screen.png)

- 『引数を追加(数値またはテキスト)』をクリックし、 **『number or text』を『ダンサーのセリフ』に変更** 後、OKボタンを押してください。

    Click "Add argument (number or text)", change "number or text" to "Dancer's line", and then click OK.

![Dancer](figure/dancer/init_screen_add_param.png)

- 以下の画面が表示されることを確認してください。

    Confirm that the following screen is displayed.

![Dancer](figure/dancer/dancer_talk_definition.png)

- 以下のブロックを画面中央にドラック＆ドロップします。

    Drag and drop the following blocks to the center of the screen.

![Common](figure/common/control_button.png) ![Common](figure/common/wait_sec.png)

![Common](figure/common/tspeech_button.png) ![Common](figure/common/speech.png)

![Common](figure/common/trans_button.png) ![Common](figure/common/trans2.png)

- ![Common](figure/common/wait_sec.png)の数字を **0.5に変更** します。(数字をダブルクリックすることで、数字を編集できる状態になります。)

    Change the number ![Common](figure/common/wait_sec.png) to 0.5.(Double-clicking on a number, you will be able to edit the number.)

![Dancer](figure/dancer/wait_sec_set.png)

- ![Common](figure/common/trans2.png)の **『こんにちわ』** に![Dancer](figure/dancer/dancer_line_param.png)をドラッグ＆ドロップ してください。

    Drag and drop the ![Dancer](figure/dancer/dancer_line_param.png) into "Hello" in ![Common](figure/common/trans2.png).

![Dancer](figure/dancer/set_dancer_line.png)

- ![Dancer](figure/dancer/set_dancer_line_small.png)の▼ボタンを押し、表示される言語の一覧から **『英語』** を選んでください。

    Press the ▼ button on ![Dancer](figure/dancer/set_dancer_line_small.png)A and select "English" from the list of languages displayed.

![Dancer](figure/dancer/set_dancer_line_english.png)

- ![Common](figure/common/speech.png)の『hello』に![Dancer](figure/dancer/set_dancer_line_english_small.png)をドラッグ＆ドロップしてください。

    Drag and drop ![Dancer](figure/dancer/set_dancer_line_english_small.png) to "hello" in ![Common](figure/common/speech.png).

![Dancer](figure/dancer/speech_connect_trans.png)

- ブロックをくっつけてください。

    Connect the blocks.

![Dancer](figure/dancer/dancer_talk_program.png)

- 以下のブロックを画面中央にドラック＆ドロップします。

    Drag and drop the following blocks to the center of the screen.

![Common](figure/common/event_button.png) ![Common](figure/common/flag.png)

![Common](figure/common/costume_button.png) ![Dancer](figure/dancer/dancer_cos_a.png)

- ![Dancer](figure/dancer/dancer_cos_a.png)の▼ボタンを押し、表示されるコスチュームの一覧から **『champ99-b』** を選んでください。

    Press ▼ on A and select "champ99-b" from the list of costumes that will display.

![Dancer](figure/dancer/dancer_cos_b.png)

- ブロックをくっつけてください。

    Connect the blocks.

![Dance](figure/dancer/dancer_init_cos.png)

- 以下のブロックを画面中央にドラック＆ドロップします。

![Common](figure/common/costume_button.png) ![Common](figure/common/costume_next.png)

![Common](figure/common/event_button.png) ![Common](figure/common/message_rcv.png)

![Common](figure/common/control_button.png) ![Common](figure/common/wait_sec.png) ![Common](figure/common/time_loop.png)

![Common](figure/common/variable_button.png) ![Common](figure/common/cat_dancer_conversation.png)

![Common](figure/common/make_block_button.png) ![Dancer](figure/dancer/dancer_talk_block.png)

![Common](figure/common/tspeech_button.png) ![Common](figure/common/voice.png)

- ![Common](figure/common/cat_dancer_conversation.png)を![Dancer](figure/dancer/dancer_talk_block.png)にドラッグ＆ドロップしてください。

    Drag and drop ![Common](figure/common/cat_dancer_conversation.png) to ![Dancer](figure/dancer/dancer_talk_block.png).

![Dancer](figure/dancer/cat_dancer_conversation_set.png)

- ![Dancer](figure/dancer/cat_dancer_conversation_set_small.png)の数字を **2に変更** します。(数字をダブルクリックすることで、数字を編集できる状態になります。)

    Change the number ![Dancer](figure/dancer/cat_dancer_conversation_set_small.png) to 2. (Double-clicking on a number, you will be able to edit the number.)

![Dancer](figure/dancer/cat_dancer_conversation_set2.png)

- ![Common](figure/common/voice.png)の▼ボタンを押し、表示される声の一覧から **『テノール』を選んでください** 。

Press the ▼ button in ![Common](figure/common/voice.png) and select "Tenor" from the list of voices displayed.

![Dancer](figure/dancer/select_and_set_voice.png)

- ![Common](figure/common/wait_sec.png)の数字を **0.5に変更** します。(数字をダブルクリックすることで、数字を編集できる状態になります。)

    Change the number ![Common](figure/common/wait_sec.png) to 0.5.(Double-clicking on a number, you will be able to edit the number.)

![Dancer](figure/dancer/wait_sec_set.png)

- ![Common](figure/common/time_loop.png)の数字を **7に変更** します。(数字をダブルクリックすることで、数字を編集できる状態になります。)

    Change the number ![Common](figure/common/time_loop.png) to 7. (Double-clicking on a number, you will be able to edit the number.)

![Dancer](figure/dancer/time_loop_change.png)

- ブロックをくっつけてください。

    Connect the blocks.

![Dancer](figure/dancer/dancer_talk_program_main.png)

- 最後に、プログラムを保存してください。

    Finally, save the program.

![Common](figure/common/save.png)
