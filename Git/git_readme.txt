�E�ƂŕҏW�����B05/20

�EGit�łł��邱��
�E��{�̃V�F���R�}���h
�EGit�̊�{�R�}���h
�Evim�i�e�L�X�g�G�f�B�^�j�̎g����
�E�u�����`�̍쐬�A�ύX�A�}�[�W
�E���|�W�g���̃N���[��
�E�N���[�����|�W�g���ւ̎捞


  
�EGIT
  ���{�W�g���i�o�b�N�A�b�v�������t�@�C��������t�H���_�j�ɑ΂��ăt�@�C���o�^���s��CUI�V�X�e���B
  ���[�L���O�f�B���N�g���Ƀt�@�C����ۑ����X�e�[�W���O�G���A�ɓo�^�����|�W�g���ɓo�^�̏��Ԃœo�^���s���B
  
  ���ۂ̃v���W�F�N�g����ł́A
  �T�[�o�̃��|�W�g�����e�����[�J���ɕ���(clone or pull)���A�ύX�����[�J�����|�W�g���ɑ΂��čs��(commit)�A
  �ŏI�I�ɃT�[�o�̃��|�W�g���ɑ΂��āA���[�J�����|�W�g���̓��e�𔽉f����(push)�菇�ƂȂ�z��B

�E��v�ȃR�}���h
git --version		�o�[�W�����m�F
git config --global user.name "kirishima"				���[�U�̓o�^
git config --global user.email"kirishima@paiza.jp"		���[���A�h���X�̓o�^
���{�W�g���̍쐬
  mkdir mywork
  cd mywork
  git init			���{�W�g���쐬�i�J�����g�t�H���_�Ƀ��|�W�g�������������j
git config --list	�ݒ����\��
git status			�t�@�C���o�^��Ԃ�\��
git status -s		�t�@�C���o�^��Ԃ��ȈՕ\��
git add ̧�ٖ�		�t�@�C�����X�e�[�W���O�֓o�^
git add .			���[�L���O�f�B���N�g�̃t�@�C�����ꊇ�ŃX�e�[�W���O�֓o�^
git commit			�X�e�[�W���O�̓��e�����|�W�g���֔��f
git commit -a		�X�e�[�W���O�{���|�W�g���ֈꊇ���f
git commit -m "commit msg"		�R�~�b�g���b�Z�[�W�𓯎��Ɏw�肷��
git log				�R�~�b�g����
git log --oneline 	�R�~�b�g���b�Z�[�W�����\��
git log -1 			�w�茏���̃R�~�b�g���b�Z�[�W��\��
git diff			�X�e�[�W���O�ƃ��[�L���O�f�B���N�g�����r
git diff --cached	�ŐV�R�~�b�g�ƃX�e�[�W���O�G���A���r
git diff HEAD		�ŐV�R�~�b�g�ƃ��[�L���O�f�B���N�g�����r
git branch			�u�����`���m�F
git branch �������	�u�����`���쐬
git checkout ̧�ٖ�	���{�W�g�����e�����[�L���O�f�B���N�g���ɖ߂�
git reset ̧�ٖ�	�X�e�[�W���O��̃t�@�C�������ɖ߂�
git revert HEAD		�ŐV�R�~�b�g�̎�����
git checkout �������	�ΏۂƂ���u�����`��ύX����
git merge �������	���݂̃u�����`�Ɏw��u�����`�𓝍�����

�������{�W�g���𕡐�����
  mkdir neko_work
  cd neko_work
  git clone /git�߽

git remote -v			���������������{�W�g���̏���\������
git pull /git�߽	    �������|�W�g���ɋ������{�W�g�����e�𔽉f����
git push origin master	�������|�W�g���̓��e���������{�W�g���ɃR�~�b�g���f����

�E���{�W�g���Ƃ�  			GIT�Ńo�b�N�A�b�v�������t�@�C��������t�H���_
�E�u�����`�Ƃ�				���{�W�g���Ƃ͕ʃo�[�W�����ŊǗ��������ꍇ�ɍ쐬����t�H���_
�E�����[�g���|�W�g���Ƃ�	�T�[�o��ɂ���GIT�̕ۑ���
�E���[�J�����|�W�g���Ƃ�	�����̃p�\�R����ɂ���ۑ���

�Evim
	�V�F���ŗ��p�ł���e�L�X�g�G�f�B�^
	- a ���݂̃J�[�\���ʒu�̉E������͂���
	- A ���݂̍s�̖����ɓ��͂���

	�R�}���h���[�h
	- �ҏW���[�h����R�}���h���[�h�ɐ؂�ւ���
	- u ���ɖ߂�
	- :wq �ۑ����ďI��
	- :q! �ۑ����Ȃ��ŏI��

�E���̑��V�F���R�}���h
	�E�t�@�C�����e��\������
	cat foo.txt

	�E�t�@�C���ꗗ��\��
	ls

	�E�t�@�C���R�s�[
	cp foo.txt bar.txt

	�E�t�@�C�����ύX
	mv bar.txt new.txt		//�t�@�C�����ύX
	mv practice test		//�t�H���_���ύX

	�E�f�B���N�g���쐬
	mkdir test

	�E�t�@�C���폜
	rm new.txt

	�E�f�B���N�g���ړ�
	cd ..
	cd practice

	�E���[�g�f�B���N�g���̈ꗗ�\��
	ls -al /

