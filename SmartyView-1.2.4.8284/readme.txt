***************************************************************************
	CakePHP1.2�{Smarty�pView�uSmartyView�v������
	Copyright 2008-2009 ECWorks ( http://www.ecworks.jp/ )
***************************************************************************

�@�_�E�����[�h���������܂��Ă��肪�Ƃ��������܂��B

�@�{�h�L�������g�ł́ASmartyView�̐ݒu���@����ѐݒ���@�ɂ��ĊȒP��
�����������Ă��������܂��B�ݒu����O�ɂ���ǂ��������܂��悤�A���肢
�\���グ�܂��B

--------------------------------------------------
���͂��߂�
--------------------------------------------------

�@�{View�N���X�́ACakePHP�ɂ�Smarty�e���v���[�g�G���W�����쓮�����邽�߂�
View��񋟂��܂��BSmarty��p���������V�X�e������̈ڐA���e�ՂɂȂ鑼�A����
View�ƈႢ�\�[�X�R�[�h���f�U�C�i�ɓn���K�v���Ȃ����߁A��ƕ��S�����m�ɂȂ�
�����b�g������܂��B�܂��A�e���v���[�g���R���p�C���������̂�ۑ����邽��
�Q��ڈȍ~�������ɋ쓮���܂����A�L���b�V���@�\�����ڂ��Ă��܂��BSmarty��
�ւ��ẮA http://www.smarty.net/ ���������������B

�@����Smarty�pView�́A�{��Bakery�ɏЉ��Ă���̂ł����A���ɌÂ��d�l�ƂȂ���
���邽�߁A�V�������K�v������܂����B�����ŁA�ŐV��view.php���x�[�X�ɁA
�V���ɍ�蒼���܂����B���̂���Bekrty�łƂ͎኱�d�l���قȂ��Ă��܂��̂ŁA������
�ۂɂ͂��C��t�����������B

--------------------------------------------------
�������
--------------------------------------------------

�@�{View�N���X�́ACakePHP1.2.4.8284 Stable���烊���C�g���č쐬���Ă��܂��B
1.2.0�ȍ~�A�������Y�����\�b�h�ɉ��ǂ�����悤�ł����A�傫�ȕύX�͂���܂���
�̂ŁA�����炭Stable�ł����瓮��\���Ǝv���܂��B

�@�����ɐ旧���āASmarty�V�X�e���ꎮ���ʓr�K�v�ɂȂ�܂��B
http://www.smarty.net/ ����ŐV�o�[�W�������_�E�����[�h���Ă����Ă��������B
����m�F�̓o�[�W����2.6.22�ɂčs���Ă���܂��B

--------------------------------------------------
�������p����
--------------------------------------------------

�@SmartyView�N���X����ѓY�t�t�@�C���ꎮ�́AMIT���C�Z���X�ɏ����������܂��B
The SmartyView's source code and attach files are distributed under THE MIT 
LICENSE.

--------------------------------------------------
���K�v�t�@�C���ƃA�b�v���[�h���@
--------------------------------------------------

�@�z�z�A�[�J�C�u���𓀂���ƁA���̃t�@�C������������܂��B�����t�@�C�����A
CakePHP���̏���̏ꏊ�ɃA�b�v���[�h���Ă��������Bempty�t�@�C���̓_�~�[
�t�@�C���̂��߁A�A�b�v���[�h�͕s�v�ł��B�܂��Aviews�f�B���N�g�����ɂ���
mypages�f�B���N�g���ȉ��A�����controllers�f�B���N�g������
mypages_controllers.php�̓T���v���ł��̂ŁA�s�v�ł�����A�b�v���[�h
���Ȃ��Ă����v�ł��B

�@[]���́A�p�[�~�b�V�����ݒ�̒l�ł��B��ʓI�Ȓl���L�ڂ���Ă��܂���
�T�[�o�[�ɂ���ĈقȂ�܂��̂œK�X�C�����Ă��������B����tmp�f�B���N�g��
�ȉ���PHP������̏������݂��s���܂��̂ŁA�������݂̏o����ݒ��
���Ă��������B

-+- cake								[***] 
 |  +- app								[755] 
 |  |  +- controllers					[755] 
 |  |  |  +- mypages_controllers.php	[644] �T���v���R���g���[��
 |  |  +- tmp							[777] 
 |  |  |  +- smarty						[777] 
 |  |  |     +- cache					[777] �L���b�V��Dir
 |  |  |        +- empty				[***] (�_�~�[�t�@�C��)
 |  |  |     +- templates_c				[777] �R���p�C��Dir
 |  |  |        +- empty				[***] (�_�~�[�t�@�C��)
 |  |  +- views							[755] 
 |  |     +- layouts					[755] 
 |  |     |  +- smarty					[755] 
 |  |     |     +- mylayouts.tpl		[644] �T���v�����C�A�E�g
 |  |     +- helpers					[755] 
 |  |     |  +- smarty.php				[644] �w���p�[�T���v��
 |  |     +- mypages					[755] 
 |  |     |  +- smarty					[755] 
 |  |     |     +- index.tpl			[644] �T���v��index�A�N�V����
 |  |     +- smarty.php					[644] SmartyView�{��
 |  +- vendors							[755] 
 |     +- smarty						[755] 
 |        +- plugins					[755] 
 |           +- empty					[***] (�_�~�[�t�@�C��)
 |        +- Smarty.class.php			}��Smarty�͕ʓr�_�E�����[�h���A
 |        ...							}�@libs�ȉ��������ɔz�u���Ă�������
 |
 +- readme.txt							[***] ���̃t�@�C��

--------------------------------------------------
���ݒ�
--------------------------------------------------

�@SmartyView�N���X���ł̐ݒ�͓��ɂ���܂���B
�@���p����R���g���[���N���X�ŁAview�v���p�e�B��'Smarty'�Ɛݒ肷�邾���ł��B

class MypagesController extends AppController {
	var $name = 'Mypages';
	var $view = 'Smarty';		//��Smarty(View)�ł��邱�Ƃ��w��
	var $layout = 'mylayout';
	
	//index�A�N�V����
	//
	function index(){
	}
}

�@��L�̏ꍇ�A/cake/app/views/layouts/smarty/mylayout.tpl�t�@�C����
���C�A�E�g�t�@�C���Ƃ��Aindex�A�N�V�����ɂ�����
/cake/app/views/mypages/smarty/index.tpl���e���v���[�g�t�@�C���Ƃ��Ďg�p
���܂��B

�@�܂��A�w���p�[����beforeRender()�AafterRender()��ݒ肷��ƁA
SmartyView���ŃR�[���o�b�N�������s���܂��B
�@����ɁAbeforeSmartyRender�EafterSmartyRender���\�b�h��ݒ肷���Smarty
�I�u�W�F�N�g���󂯎���ăR�[���o�b�N���������邱�Ƃ��o���܂�(��q�Q��)�B

--------------------------------------------------
��SmartyView�g���@�\
--------------------------------------------------

�@�W��View�ƈႢ�ASmartyView�ɂ͎��̊g���@�\������܂��B

�ybeforeSmartyRender�����afterSmartyRender�R�[���o�b�N�@�\�z

�@�W��View�ł́AHelper���ɁubeforeRender/beforeLayout/afterLayout/
afterRender�v�R�[���o�b�N��t�����邱�ƂŁA�����_�����O�O�y�ь�ɏ�����
�s�����Ƃ��o���܂����A���̑���ɁubeforeSmartyRender/beforeSmartyLayout/
afterSmartyLayout/afterSmartyRender�v�R�[���o�b�N��ݒu���邱�ƂŁA
Smarty�I�u�W�F�N�g�̃��t�@�����X���󂯎���ď������邱�Ƃ��o���܂��B

class MyHelper extends Helper {

	function beforeSmartyRender(&$smarty){
		//...
	}
	
	function beforeSmartyLayout(&$smarty){
		//...
	}
	
	function afterSmartyLayout(&$smarty){
		//...
	}
	
	function afterSmartyRender(&$smarty){
		//...
	}
}

��beforeRender/beforeLayout/afterLayout/afterRender���c���Ă���܂��B
�@��������鏇�Ԃ͎��̒ʂ�ł��B
�@beforeRender �� beforeSmartyRender	��������
�@beforeLayout �� beforeSmartyLayout	��
�@afterLayout �� afterSmartyLayout		��
�@afterRender �� afterSmartyRender		��


�yShiftJIS�ɂ�SmartyView���g�����߂�Tips�z

�@�g�уT�C�g�Ȃ�ShiftJIS��p�����T�C�g�̐����Smarty��p�������ꍇ�����邩��
�v���܂����ASmarty�f�t�H���g�̃f�~���^�u{}�v�̂܂܂ł́A�������������Ă��܂�
���������삳���邱�Ƃ��o���܂���B
�@�����ŁA�f�~���^���Ⴄ���̂ɕύX����K�v���o�Ă���̂ł����A�R���g���[������
SmartyView���ɂ���Smarty�C���X�^���X�ɒ��ڃA�N�Z�X���邱�Ƃ͏o���܂���B

�@�����ŁA���O�Ńw���p�[��p�ӂ��邱�ƂŁA�R���g���[������Smarty�C���X�^���X��
���ڃf�~���^��ݒ肷�邱�ƂŁA���̖����������邱�Ƃ��o���܂��B

class SmartyHelper extends Helper {

	function beforeSmartyRender(&$smarty){
		
		//Smarty�f�~���^�̕ύX
		//
		$smarty->left_delimiter = '{{';
		$smarty->right_delimiter = '}}';
	}

}

���Ȃ��A��L�Q�_�Ɋւ��܂��Ă̓T���v�����p�ӂ��܂����̂ŁA�T���v���t�@�C����
�@�����Q�l�ɂ��Ă��������B


--------------------------------------------------
�����ӌ��E�����z�E�s��񍐂Ȃ�
--------------------------------------------------

�@���ӌ��A�����z�Ȃǂ́A�����̃u���O����p�T�C�g�̃R�����g���ɏ��������
���������܂��ƍK���ł��B

��ECWorks
http://www.ecworks.jp/

��ECWorks blog
http://blog.ecworks.jp/

��SmartyView�T�|�[�g�y�[�W
http://blog.ecworks.jp/smartyview

�yCM�z
�@�e���v���[�g�t�@�C����e�Ղɍ쐬�E�z�u���邽�߂̃c�[���uTplcutter�v��
���J���Ă��܂��B����Dreamweaver���̃T�C�g�f�U�C���c�[���𗘗p���Ă̐����
��ϕ֗��ł��B����������񂲗��p���������I

--------------------------------------------------
���o�[�W�������
--------------------------------------------------

�yVer1.2.4.8284�z2009.08.10
�@CakePHP1.2.4.8286 Stable�Ή��o�[�W�����B

�yVer1.2.1.8004�z2009.02.25
�@CakePHP1.2.1.8004 Stable�Ή��o�[�W�����B
�@�EbeforeSmartyLayout/afterSmartyLayout�R�[���o�b�N��V�݂��܂����B
�@�ERC2�Ɣ�ׁA�L���b�V���̌Ă΂�����኱�قȂ��Ă��܂�(view.php�R��)�B
�@�ERC2�Ɣ�ׁAbeforeRender/beforeLayout/afterLayout/afterRender�̌Ă΂����
�@�@�኱�قȂ��Ă��܂�(view.php�R��)�B
�@�E�T���v���e���v���[�g���C�����܂����B
�@�E�T���v���w���p�[��ǉ����܂����B

�yVer1.2.0.7296�z2008.07.07
�@CakePHP1.2.0.7296(RC2)�Ή��o�[�W�����B
�@�ERC1�Ɣ�ׁAhelper�̌Ă΂�����኱�قȂ��Ă��܂�(view.php�R��)�B
�@�ECache:view���ۑ�����Ȃ��Ȃ�܂���(view.php�R��)�B
�@�E�T���v���e���v���[�g���C�����܂����B

�yVer1.2.0.7119�z2008.06.25
�@CakePHP1.2.0.7311(RC1)�Ή��o�[�W�����B
�@�EVendor�֐����p�~�ƂȂ������߁AApp:import()�ɂđΉ����܂����B
�@�Ewebservice���p�~�ƂȂ������߁A_getViewFileName()���\�b�h�����
�@�@_getLayoutFileName()���\�b�h���폜���܂����B
�@�EView�L���b�V���ɑΉ����܂���(Smarty�L���b�V���͖����ƂȂ��Ă��܂�)�B

�yVer1.2.0.6311�z2008.06.25
�@CakePHP1.2.0.6311(beta)�Ή��o�[�W�����B
�@�EafterSmartyRender()�R�[���o�b�N���Ă΂�Ȃ��s����C�����܂����B
�@�E�@�\���Ă��Ȃ������L���b�V���w����폜���܂����B

�yVer1.2.0.1�z2008.04.17
�@�E�ϐ��̎Q�ƕ��@���s�K�؂���������PHP5�ŕs����o�Ă����ӏ����C�����܂����B

�yVer1.2.0.0�z2008.02.01
�@���J�o�[�W����
�@(CakePHP�̃o�[�W�����ɍ��킹�����߁A����ȑO�̃i���o�[�͌��Ԃł�)


**************************************************
�@�@ECWorks(H.N MASA-P)
�@�@http://www.ecworks.jp/
**************************************************
