# Sources for autoinstallation

module_DATA = \
  modules/AutoinstStorage.rb \
  modules/AutoinstPartPlan.rb \
  modules/AutoInstallRules.rb \
  modules/Y2ModuleConfig.rb \
  modules/ProfileLocation.rb \
  modules/AutoinstPartition.rb \
  modules/AutoinstClone.rb \
  modules/AutoinstImage.rb \
  modules/AutoinstConfig.rb \
  modules/Profile.rb \
  modules/AutoinstCommon.rb \
  modules/AutoinstFile.rb \
  modules/AutoinstScripts.rb \
  modules/AutoInstall.rb \
  modules/AutoinstGeneral.rb \
  modules/AutoinstSoftware.rb \
  modules/AutoinstDrive.rb \
  modules/AutoinstClass.rb \
  modules/AutoinstFunctions.rb

client_DATA = \
  clients/classes_auto.rb \
  clients/ayast_setup.rb \
  clients/scripts_auto.rb \
  clients/software_auto.rb \
  clients/general_auto.rb \
  clients/inst_autopost.rb \
  clients/storage_auto.rb \
  clients/ayast_probe.rb \
  clients/inst_autoconfigure.rb \
  clients/inst_autosetup_upgrade.rb \
  clients/autoinst_scripts2_finish.rb \
  clients/inst_autosetup.rb \
  clients/inst_autoinit.rb \
  clients/report_auto.rb \
  clients/autoinst_scripts1_finish.rb \
  clients/inst_autoimage.rb \
  clients/inst_store_upgrade_software.rb \
  clients/files_auto.rb \
  clients/autoinst_test_clone.rb \
  clients/autoyast.rb \
  clients/clone_system.rb \
  clients/autoinst_test_stage.rb

yncludedir = @yncludedir@/autoinstall
ynclude_DATA = \
  include/autoinstall/DriveDialog.rb \
  include/autoinstall/io.rb \
  include/autoinstall/wizards.rb \
  include/autoinstall/autoinst_dialogs.rb \
  include/autoinstall/classes.rb \
  include/autoinstall/types.rb \
  include/autoinstall/PartitionDialog.rb \
  include/autoinstall/StorageDialog.rb \
  include/autoinstall/tree.rb \
  include/autoinstall/common.rb \
  include/autoinstall/dialogs.rb \
  include/autoinstall/AdvancedPartitionDialog.rb \
  include/autoinstall/ask.rb \
  include/autoinstall/VolgroupDialog.rb \
  include/autoinstall/xml.rb \
  include/autoinstall/script_dialogs.rb \
  include/autoinstall/conftree.rb \
  include/autoinstall/helps.rb \
  include/autoinstall/general_dialogs.rb

ylibdir = @ylibdir@/autoinstall
ylib_DATA = \
  lib/autoinstall/activate_callbacks.rb \
  lib/autoinstall/module_config_builder.rb \
  lib/autoinstall/pkg_gpg_check_handler.rb \
  lib/autoinstall/partitioning_preprocessor.rb \
  lib/autoinstall/autosetup_helpers.rb \
  lib/autoinstall/storage_proposal.rb \
  lib/autoinstall/autoinst_issues_presenter.rb \
  lib/autoinstall/autoinst_issues.rb \
  lib/autoinstall/storage_proposal_issues_presenter.rb

ydialogsdir = @ylibdir@/autoinstall/dialogs
ydialogs_DATA = \
  lib/autoinstall/dialogs/disk_selector.rb \
  lib/autoinstall/dialogs/question.rb

yclientsdir = @ylibdir@/autoinstall/clients
yclients_DATA = \
  lib/autoinstall/clients/ayast_probe.rb

ycautoinst_issuesdir = @ylibdir@/autoinstall/autoinst_issues
ycautoinst_issues_DATA = \
  lib/autoinstall/autoinst_issues/invalid_value.rb \
  lib/autoinstall/autoinst_issues/issue.rb \
  lib/autoinstall/autoinst_issues/list.rb \
  lib/autoinstall/autoinst_issues/missing_value.rb

scrconf_DATA = \
  scrconf/cfg_autoinstall.scr \
  scrconf/autoinstall.scr

schemafilesdir = $(schemadir)/autoyast/rnc
schemafiles_DATA = \
  autoyast-rnc/scripts.rnc \
  autoyast-rnc/rules.rnc \
  autoyast-rnc/common.rnc \
  autoyast-rnc/pxe.rnc \
  autoyast-rnc/classes-use.rnc \
  autoyast-rnc/classes-decl.rnc \
  autoyast-rnc/software.rnc \
  autoyast-rnc/reporting.rnc \
  autoyast-rnc/partitioning.rnc \
  autoyast-rnc/profile-misc.rnc \
  autoyast-rnc/general.rnc \
  autoyast-rnc/files.rnc

ybin_SCRIPTS = \
  bin/autoyast-initscripts.sh \
  bin/fetch_image.sh

desktop_DATA = \
  desktop/autoyast.desktop \
  desktop/clone_system.desktop

fillup_DATA = \
  fillup/sysconfig.autoinstall

symbolicdir = @icondir@/hicolor/symbolic/apps
symbolic_DATA = \
  icons/hicolor/symbolic/apps/yast-autoyast-symbolic.svg
scalabledir = @icondir@/hicolor/scalable/apps
scalable_DATA = \
  icons/hicolor/scalable/apps/yast-autoyast.svg

EXTRA_DIST = $(module_DATA) $(client_DATA) $(ynclude_DATA) $(scrconf_DATA) $(schemafiles_DATA) $(ybin_SCRIPTS) $(desktop_DATA) $(fillup_DATA) $(ylib_DATA) $(ydialogs_DATA) $(yclients_DATA) $(symbolic_DATA) $(scalable_DATA)

include $(top_srcdir)/Makefile.am.common
