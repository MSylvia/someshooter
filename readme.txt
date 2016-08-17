---------------------------
 Attention
---------------------------
- After uploading this game sketch, you may not be able to uploading next game sketch. If you get the error message below, please use the recover method below to upload the next sketch:
  - Error message:
    - "Couldn't find a Board on the selected port. Check that you have the correct port selected.  If it is correct, try pressing the board's reset button after initiating the upload."
  - Recover method (PORTS-Reset Method):
    (1) Please set: ArduinoIDE > File > Preferences > Settings > Show verbose output during: upload = checked
    (2) Keep to press a reset button of Arduboy at the side of the USB cable.
    (3) Push upload button of Arduino IDE.
    (4) Release the reset button of Arduboy when a message "PORTS {} / {} => {}" is output continuously.
---------------------------
 ������
---------------------------
- ���̃Q�[���̃X�P�b�`��]��������Ɏ��̃Q�[���̃X�P�b�`���A�b�v���[�h�ł��Ȃ��Ȃ邩������܂���B�������L�̂悤�ȃG���[���b�Z�[�W���ł���A���L�̏C�����@�ŏC�����A���̃X�P�b�`��]�����Ă��������B
  - �G���[���b�Z�[�W:
    - "Couldn't find a Board on the selected port. Check that you have the correct port selected.  If it is correct, try pressing the board's reset button after initiating the upload."
  - �C�����@(PORTS-���Z�b�g�@):
    (1) ArduinoIDE > �t�@�C�� > ���ݒ�> �ݒ� > ���ڍׂȏ���\������: �������� = �`�F�b�N�L�ɂ��܂��B
    (2) Arduboy ��USB�P�[�u���̉��̃��Z�b�g�{�^�����������܂܂ɂ���B(�ܗk�}�̐��ܐ؂��1mm�؂������̂��g���ƕ֗��ł�)
    (3) Arduino IDE �̏������݃{�^���������܂��B
    (4) Arduino IDE �� "PORTS {} / {} => {}" �Ƃ������b�Z�[�W���A�����ďo�͂�����Ԃ̎��� Arduboy �̃��Z�b�g�{�^���𗣂��܂��B 

---------------------------
Tested Environment
---------------------------
- Arduboy 1.0
- Arduboy Library:
  - https://github.com/Arduboy/Arduboy/
  - revision: 3c409fefb
  - branch  : master
- Arduino IDE 1.6.9
---------------------------
Description  
---------------------------
- This is a shooter game !
- Shoot circle enemies.
- The line at bottom is your hit point.
- The line at above that is enemy's hit point.
- Key:
  - UDLR ... move
  - B    ... shot
  - A    ... none
--------------------------------
EOF