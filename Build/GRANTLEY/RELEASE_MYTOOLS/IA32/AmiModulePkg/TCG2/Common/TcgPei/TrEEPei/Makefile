#
# DO NOT EDIT
# This file is auto-generated by build utility
#
# Module Name:
#
#   Makefile
#
# Abstract:
#
#   Auto-generated makefile for building modules, libraries or platform
#
    

#
# Platform Macro Definition
#
PLATFORM_NAME = GRANTLEY
PLATFORM_GUID = A361BEE1-AEB7-4921-8505-A323899516E6
PLATFORM_VERSION = 1
PLATFORM_RELATIVE_DIR = Build
PLATFORM_DIR = $(WORKSPACE)\Build
PLATFORM_OUTPUT_DIR = Build\GRANTLEY

#
# Module Macro Definition
#
MODULE_NAME = TrEEPei
MODULE_GUID = 961C19BE-D1AC-4ba7-87AF-4AE0F09DF2A6
MODULE_NAME_GUID = TrEEPei
MODULE_VERSION = 1.0
MODULE_TYPE = PEIM
MODULE_FILE = TrEEPei.inf
MODULE_FILE_BASE_NAME = TrEEPei
BASE_NAME = $(MODULE_NAME)
MODULE_RELATIVE_DIR = AmiModulePkg\TCG2\Common\TcgPei
PACKAGE_RELATIVE_DIR = TCG2\Common\TcgPei
MODULE_DIR = $(WORKSPACE)\AmiModulePkg\TCG2\Common\TcgPei

MODULE_ENTRY_POINT = TrEEPeiEntry
ARCH_ENTRY_POINT = TrEEPeiEntry
IMAGE_ENTRY_POINT = _ModuleEntryPoint

INF_VERSION = 0x00010005
VERSION_STRING = 1.0
BASE_NAME = TrEEPei
MODULE_TYPE = PEIM
FILE_GUID = 961C19BE-D1AC-4ba7-87AF-4AE0F09DF2A6

#
# Build Configuration Macro Definition
#
ARCH = IA32
TOOLCHAIN = MYTOOLS
TOOLCHAIN_TAG = MYTOOLS
TARGET = RELEASE

#
# Build Directory Macro Definition
#
# PLATFORM_BUILD_DIR = c:\1218_alibaba\Build\GRANTLEY\RELEASE_MYTOOLS
BUILD_DIR = c:\1218_alibaba\Build\GRANTLEY\RELEASE_MYTOOLS
BIN_DIR = $(BUILD_DIR)\IA32
LIB_DIR = $(BIN_DIR)
MODULE_BUILD_DIR = c:\1218_alibaba\Build\GRANTLEY\RELEASE_MYTOOLS\IA32\AmiModulePkg\TCG2\Common\TcgPei\TrEEPei
OUTPUT_DIR = c:\1218_alibaba\Build\GRANTLEY\RELEASE_MYTOOLS\IA32\AmiModulePkg\TCG2\Common\TcgPei\TrEEPei\OUTPUT
DEBUG_DIR = c:\1218_alibaba\Build\GRANTLEY\RELEASE_MYTOOLS\IA32\AmiModulePkg\TCG2\Common\TcgPei\TrEEPei\DEBUG
DEST_DIR_OUTPUT = $(OUTPUT_DIR)
DEST_DIR_DEBUG = $(DEBUG_DIR)

#
# Shell Command Macro
#
RD = rmdir /s /q
RM = del /f /q
MD = mkdir
CP = copy /y
MV = move /y


#
# Tools definitions specific to this module
#
SYMRENAME =  echo
SYMRENAME_FLAGS = Symbol renaming not needed for

CBINDLINK_FLAGS = /nologo /NODEFAULTLIB /NOENTRY /DLL /ALIGN:16

ASLDLINK =  C:\WinDDK_7600.16385.1\WinDDk\WinDDK\7600.16385.1\bin\x86\x86\link.exe
ASLDLINK_FLAGS = /nologo /NODEFAULTLIB /ENTRY:ReferenceAcpiTable /SUBSYSTEM:EFI_BOOT_SERVICE_DRIVER

DT =  C:/Aptio_5.x_TOOLS_29/Tools/iasl5

VFR =  VfrCompile
VFR_FLAGS = -n

PP =  C:\WinDDK_7600.16385.1\WinDDk\WinDDK\7600.16385.1\bin\x86\x86\cl.exe
PP_FLAGS = /nologo /E /TC /FIAutoGen.h

LZMAF86 =  LzmaF86Compress
LZMAF86_GUID =  D42AE6BD-1352-4bfb-909A-CA72A6EAE889

GENFW =  GenFw
GENFW_FLAGS = 

DLINK =  C:\WinDDK_7600.16385.1\WinDDk\WinDDK\7600.16385.1\bin\x86\x86\link.exe
DLINK_FLAGS = /MACHINE:I386 /NOLOGO /NODEFAULTLIB /IGNORE:4001 /OPT:REF /OPT:ICF=10 /MAP /ALIGN:32 /SECTION:.xdata,D /SECTION:.pdata,D /LTCG /DLL /ENTRY:$(IMAGE_ENTRY_POINT) /SUBSYSTEM:EFI_BOOT_SERVICE_DRIVER /SAFESEH:NO /BASE:0 /DRIVER /MERGE:.data=.text /MERGE:.rdata=.text /IGNORE:4254 /PDB:$(DEBUG_DIR)/$(BASE_NAME).pdb

SLINK =  C:\WinDDK_7600.16385.1\WinDDk\WinDDK\7600.16385.1\bin\x86\x86\link.exe /LIB
SLINK_FLAGS = /nologo /LTCG

ASM =  ml.exe
ASM_FLAGS = /nologo /c /WX /W3 /Cx /Zd /coff

ASL =  C:/Aptio_5.x_TOOLS_29/Tools/iasl5 #AptioV server override
ASL_FLAGS = 
ASL_OUTFLAGS =  -cr -p #AptioV server override: Flag added to skip resource descriptor checks

TIANO =  TianoCompress
TIANO_GUID =  A31280AD-481E-41B6-95E8-127F4C984779

CC =  C:\WinDDK_7600.16385.1\WinDDk\WinDDK\7600.16385.1\bin\x86\x86\cl.exe
CC_FLAGS = /nologo /c /WX /GS- /W3 /Gs32768 /Gy /D UNICODE /GL /FIAutoGen.h /EHs-c- /GR- /GF -D PI_SPECIFICATION_VERSION=0x1001E -D EFI_SPECIFICATION_VERSION=0x20028 /wd4819 /O1ib2 -DMDEPKG_NDEBUG /D CRB_FLAG /D VFR_CRB_FLAG /D EXTERNAL_PACKAGE /D SSA_FLAG /D SSA_LOADER_FLAG /D HSX_HOST /D BDX_HOST /D LT_FLAG /DTRAD_FLAG=1 /DPCH_SERVER_BIOS_FLAG=1 /DPCH_SERVER_BIOS_FLAG=1 /DME_SUPPORT_FLAG=1 /DSPS_SUPPORT=1 /DPFAT_FLAG=1 /D AMI_PAM_SAVE_RESTORE_SWSMI_VALUE=0xBE /D AMI_PAM_SAVE_CMD=0xE0 /D AMI_PAM_RESTORE_CMD=0xE1 /DUSB_PRECONDITION_ENABLE_FLAG=1 /DWDT_SUPPORT_ENABLED=1

VFRPP =  C:\WinDDK_7600.16385.1\WinDDk\WinDDK\7600.16385.1\bin\x86\x86\cl.exe
VFRPP_FLAGS = /nologo /E /TC /DVFRCOMPILE /FI$(MODULE_NAME)StrDefs.h -D PI_SPECIFICATION_VERSION=0x1001E -D EFI_SPECIFICATION_VERSION=0x20028 /wd4819 /O1ib2 -DMDEPKG_NDEBUG /D CRB_FLAG /D VFR_CRB_FLAG /D EXTERNAL_PACKAGE /D SSA_FLAG /D SSA_LOADER_FLAG /D HSX_HOST /D BDX_HOST /D LT_FLAG /DTRAD_FLAG=1 /DPCH_SERVER_BIOS_FLAG=1 /DPCH_SERVER_BIOS_FLAG=1 /DME_SUPPORT_FLAG=1 /DSPS_SUPPORT=1 /DPFAT_FLAG=1 /D AMI_PAM_SAVE_RESTORE_SWSMI_VALUE=0xBE /D AMI_PAM_SAVE_CMD=0xE0 /D AMI_PAM_RESTORE_CMD=0xE1 /DUSB_PRECONDITION_ENABLE_FLAG=1 /DWDT_SUPPORT_ENABLED=1

LZMA =  LzmaCompress
LZMA_GUID =  EE4E5898-3914-4259-9D6E-DC7BD79403CF

ASM16 =  ml.exe

ASLCC =  C:\WinDDK_7600.16385.1\WinDDk\WinDDK\7600.16385.1\bin\x86\x86\cl.exe
ASLCC_FLAGS = /nologo /c /TC /FIAutoGen.h /Dmain=ReferenceAcpiTable

CBINCC_FLAGS = /nologo /c /TC /Os /FIAutoGen.h

APP =  C:\WinDDK_7600.16385.1\WinDDk\WinDDK\7600.16385.1\bin\x86\x86\cl.exe
APP_FLAGS = /nologo /E /TC

OPTROM =  EfiRom
OPTROM_FLAGS = -e

NASMB_FLAGS = -f bin

VPDTOOL =  BPDG
VPDTOOL_GUID =  8C3D856A-9BE6-468E-850A-24F7A8D38E08

ASLPP =  C:\WinDDK_7600.16385.1\WinDDk\WinDDK\7600.16385.1\bin\x86\x86\cl.exe
ASLPP_FLAGS = /nologo /EP /TC

OBJCOPY =  echo
OBJCOPY_FLAGS = objcopy not needed for

MAKE =  nmake.exe

ASMLINK =  link16.exe
ASMLINK_FLAGS = /nologo /tiny

NASM =  nasm
NASM_FLAGS = -Ox -f win32


MAKE_FILE = $(MODULE_BUILD_DIR)\Makefile

#
# Build Macro
#
OBJECT_FILES =  \
    $(OUTPUT_DIR)\TrEEPei.obj \
    $(OUTPUT_DIR)\AutoGen.obj

STATIC_LIBRARY_FILES =  \
    $(BIN_DIR)\MdePkg\Library\PeiHobLib\PeiHobLib\OUTPUT\PeiHobLib.lib \
    $(BIN_DIR)\MdePkg\Library\PeiMemoryAllocationLib\PeiMemoryAllocationLib\OUTPUT\PeiMemoryAllocationLib.lib \
    $(BIN_DIR)\MdePkg\Library\PeiPcdLib\PeiPcdLib\OUTPUT\PeiPcdLib.lib \
    $(BIN_DIR)\MdePkg\Library\BaseMemoryLibRepStr\BaseMemoryLibRepStr\OUTPUT\BaseMemoryLibRepStr.lib \
    $(BIN_DIR)\MdePkg\Library\PeiServicesTablePointerLibIdt\PeiServicesTablePointerLibIdt\OUTPUT\PeiServicesTablePointerLibIdt.lib \
    $(BIN_DIR)\MdePkg\Library\PeiServicesLib\PeiServicesLib\OUTPUT\PeiServicesLib.lib \
    $(BIN_DIR)\AmiModulePkg\Library\PeiAmiDebugLib\PeiAmiDebugLib\OUTPUT\PeiAmiDebugLib.lib \
    $(BIN_DIR)\MdePkg\Library\BaseLib\BaseLib\OUTPUT\BaseLib.lib \
    $(BIN_DIR)\MdePkg\Library\BaseIoLibIntrinsic\BaseIoLibIntrinsic\OUTPUT\BaseIoLibIntrinsic.lib \
    $(BIN_DIR)\MdePkg\Library\BasePciExpressLib\BasePciExpressLib\OUTPUT\BasePciExpressLib.lib \
    $(BIN_DIR)\MdePkg\Library\BasePciLibPciExpress\BasePciLibPciExpress\OUTPUT\BasePciLibPciExpress.lib \
    $(BIN_DIR)\AmiModulePkg\TCG2\ShaLib\TcgHashIntrinsicLib\OUTPUT\TcgHashIntrinsicLib.lib \
    $(BIN_DIR)\MdePkg\Library\BasePostCodeLibPort80\BasePostCodeLibPort80\OUTPUT\BasePostCodeLibPort80.lib \
    $(BIN_DIR)\GrantleyPkg\Library\IntelIchAcpiTimerLib\IntelIchAcpiTimerLib\OUTPUT\IntelIchAcpiTimerLib.lib \
    $(BIN_DIR)\AmiModulePkg\TCG2\ShaLib\ShaLib\OUTPUT\ShaLib.lib \
    $(BIN_DIR)\AmiModulePkg\TCG2\CRB_lib\PttHciLibNull\OUTPUT\PttHciDeviceNullLib.lib \
    $(BIN_DIR)\AmiModulePkg\TCG2\CRB_lib\PspfTpmLibNull\OUTPUT\PspfTpmLibNull.lib \
    $(BIN_DIR)\AmiCompatibilityPkg\Library\AmiPeiLib\OUTPUT\AmiPeiLib.lib \
    $(BIN_DIR)\AmiModulePkg\TCG2\TisLib\TisLib32\OUTPUT\TisLib32.lib \
    $(BIN_DIR)\MdePkg\Library\PeimEntryPoint\PeimEntryPoint\OUTPUT\PeimEntryPoint.lib \
    $(BIN_DIR)\AmiModulePkg\TCG2\Common\AmiTcmlib\AmiTcmlib\OUTPUT\AmiTcmlib.lib \
    $(BIN_DIR)\Build\Tpm20CRBLibPei\OUTPUT\CrbLibPei.lib \
    $(BIN_DIR)\AmiModulePkg\TCG2\Common\AmiTcgPlatformPei\AmiTcgLibPei\OUTPUT\AmiTcgLibPei.lib \
    $(OUTPUT_DIR)\TrEEPei.lib

INC =  \
    /I$(WORKSPACE)\AmiModulePkg\TCG2\Common\TcgPei \
    /I$(DEBUG_DIR) \
    /I$(WORKSPACE)\AmiCompatibilityPkg \
    /I$(WORKSPACE)\AmiCompatibilityPkg\Include \
    /I$(WORKSPACE)\Build \
    /I$(WORKSPACE) \
    /I$(WORKSPACE)\AmiModulePkg\Include \
    /I$(WORKSPACE)\MdePkg\Include \
    /I$(WORKSPACE)\MdeModulePkg\Include \
    /I$(WORKSPACE)\IntelFrameworkPkg\Include \
    /I$(WORKSPACE)\IntelFrameworkModulePkg\Include \
    /I$(WORKSPACE)\AmiTsePkg\Include \
    /I$(WORKSPACE)\GrantleyPkg\Include \
    /I$(WORKSPACE)\GrantleySocketPkg\Include \
    /I$(WORKSPACE)\GrantleySocketPkg\Library\MemoryQpiInit\Chip\Include \
    /I$(WORKSPACE)\GrantleySocketPkg\Library\MemoryQpiInit\Core\Include \
    /I$(WORKSPACE)\GrantleySocketPkg\Library\MemoryQpiInit\Platform\Include \
    /I$(WORKSPACE)\ServerCommonPkg\Include \
    /I$(WORKSPACE)\GrantleyPkg\Override\Restricted\IA32FamilyCpuPkg\Include \
    /I$(WORKSPACE)\AmiModulePkg \
    /I$(WORKSPACE)\MdePkg \
    /I$(WORKSPACE)\MdePkg\Include\Ia32

OBJECT_FILES_LIST = c:\1218_alibaba\Build\GRANTLEY\RELEASE_MYTOOLS\IA32\AmiModulePkg\TCG2\Common\TcgPei\TrEEPei\OUTPUT\object_files.lst
STATIC_LIBRARY_FILES_LIST = c:\1218_alibaba\Build\GRANTLEY\RELEASE_MYTOOLS\IA32\AmiModulePkg\TCG2\Common\TcgPei\TrEEPei\OUTPUT\static_library_files.lst


COMMON_DEPS = $(WORKSPACE)\AmiModulePkg\Include\AmiTcg\TcgMisc.h \
              $(WORKSPACE)\MdePkg\Include\Ppi\CpuIo.h \
              $(WORKSPACE)\MdePkg\Include\Uefi\UefiBaseType.h \
              $(WORKSPACE)\MdePkg\Include\Uefi\UefiMultiPhase.h \
              $(WORKSPACE)\AmiCompatibilityPkg\Include\Efi.h \
              $(WORKSPACE)\Build\token.h \
              $(WORKSPACE)\MdePkg\Include\Library\BaseLib.h \
              $(WORKSPACE)\MdePkg\Include\Pi\PiFirmwareVolume.h \
              $(WORKSPACE)\IntelFrameworkPkg\Include\Guid\FirmwareFileSystem.h \
              $(WORKSPACE)\MdePkg\Include\PiPei.h \
              $(WORKSPACE)\MdePkg\Include\Guid\SalSystemTable.h \
              $(WORKSPACE)\MdePkg\Include\Guid\FirmwareFileSystem2.h \
              $(WORKSPACE)\MdePkg\Include\Pi\PiMultiPhase.h \
              $(WORKSPACE)\MdePkg\Include\Library\DebugLib.h \
              $(WORKSPACE)\MdePkg\Include\Uefi\UefiGpt.h \
              $(WORKSPACE)\MdePkg\Include\Protocol\SimpleTextOut.h \
              $(WORKSPACE)\MdePkg\Include\Library\BaseMemoryLib.h \
              $(WORKSPACE)\MdePkg\Include\Ppi\PciCfg2.h \
              $(WORKSPACE)\AmiModulePkg\Include\PPI\TcgPlatformSetupPeiPolicy.h \
              $(WORKSPACE)\MdePkg\Include\Pi\PiStatusCode.h \
              $(WORKSPACE)\MdePkg\Include\Protocol\DevicePath.h \
              $(WORKSPACE)\AmiModulePkg\Include\AmiTcg\TcmPc.h \
              $(WORKSPACE)\MdePkg\Include\Uefi\UefiSpec.h \
              $(WORKSPACE)\MdePkg\Include\Guid\MemoryAllocationHob.h \
              $(WORKSPACE)\MdePkg\Include\Pi\PiHob.h \
              $(WORKSPACE)\MdePkg\Include\IndustryStandard\Tpm12.h \
              $(WORKSPACE)\AmiModulePkg\Include\AmiTcg\TpmLib.h \
              $(WORKSPACE)\MdePkg\Include\uefi.h \
              $(WORKSPACE)\AmiModulePkg\Include\AmiTcg\INTTcgAcpi.h \
              $(WORKSPACE)\MdePkg\Include\Ppi\ReadOnlyVariable2.h \
              $(WORKSPACE)\AmiModulePkg\Include\AmiTcg\Sha.h \
              $(WORKSPACE)\MdePkg\Include\Uefi\UefiPxe.h \
              $(WORKSPACE)\AmiModulePkg\Include\AmiTcg\TCGMisc.h \
              $(WORKSPACE)\MdePkg\Include\Protocol\DebugSupport.h \
              $(WORKSPACE)\MdePkg\Include\Guid\HiiFormMapMethodGuid.h \
              $(WORKSPACE)\AmiModulePkg\Include\AmiTcg\TcgTpm12.h \
              $(WORKSPACE)\MdePkg\Include\PPI\LoadFile.h \
              $(WORKSPACE)\AmiCompatibilityPkg\Include\FFS.h \
              $(WORKSPACE)\AmiModulePkg\Include\AmiTcg\TcgEfi12.h \
              $(DEBUG_DIR)\AutoGen.h \
              $(WORKSPACE)\MdePkg\Include\IndustryStandard\UefiTcgPlatform.h \
              $(WORKSPACE)\AmiModulePkg\Include\AmiTcg\Tpm20Pei.h \
              $(WORKSPACE)\MdePkg\Include\Guid\Mps.h \
              $(WORKSPACE)\MdePkg\Include\Pi\PiPeiCis.h \
              $(WORKSPACE)\MdePkg\Include\Pi\PiFirmwareFile.h \
              $(WORKSPACE)\AmiModulePkg\Include\PPI\TcgService.h \
              $(WORKSPACE)\MdePkg\Include\Pi\PiS3BootScript.h \
              $(WORKSPACE)\MdePkg\Include\Ia32\ProcessorBind.h \
              $(WORKSPACE)\AmiModulePkg\Include\PPI\TpmDevice.h \
              $(WORKSPACE)\AmiModulePkg\Include\AmiTcg\Tpm20.h \
              $(WORKSPACE)\AmiModulePkg\Include\PPI\AmiTreePpi.h \
              $(WORKSPACE)\MdePkg\Include\IndustryStandard\PeImage.h \
              $(WORKSPACE)\MdePkg\Include\Pi\PiBootMode.h \
              $(WORKSPACE)\AmiModulePkg\Include\AmiTcg\TcgCommon.h \
              $(WORKSPACE)\MdePkg\Include\Protocol\SimpleTextIn.h \
              $(WORKSPACE)\MdePkg\Include\Pi\PiDependency.h \
              $(WORKSPACE)\MdePkg\Include\Library\PeiServicesTablePointerLib.h \
              $(WORKSPACE)\AmiModulePkg\Include\AmiTcg\ZTEICTcmOrdinals.h \
              $(WORKSPACE)\MdePkg\Include\Guid\WinCertificate.h \
              $(WORKSPACE)\Build\Token.h \
              $(WORKSPACE)\MdePkg\Include\PPI\CpuIo.h \
              $(WORKSPACE)\MdePkg\Include\Base.h \
              $(WORKSPACE)\MdePkg\Include\Uefi\UefiInternalFormRepresentation.h \
              $(WORKSPACE)\AmiModulePkg\Include\AmiTcg\TcgEfiTpm.h \
              $(WORKSPACE)\AmiModulePkg\Include\AmiTcg\TcgPc.h \
              $(WORKSPACE)\MdePkg\Include\Guid\SmBios.h \
              $(WORKSPACE)\MdePkg\Include\Protocol\SimpleTextInEx.h \
              $(WORKSPACE)\MdePkg\Include\Guid\Acpi.h \
              $(WORKSPACE)\MdePkg\Include\Guid\GlobalVariable.h \
              $(WORKSPACE)\AmiCompatibilityPkg\Include\EFI.h \
              $(WORKSPACE)\MdePkg\Include\Protocol\StatusCode.h \
              $(WORKSPACE)\MdePkg\Include\UEFI.h \
              $(WORKSPACE)\MdePkg\Include\Uefi.h \
              $(WORKSPACE)\MdePkg\Include\Guid\EventGroup.h \
              $(WORKSPACE)\AmiCompatibilityPkg\Include\HOB.h \
              $(WORKSPACE)\MdePkg\Include\Guid\PcAnsi.h \
              

#
# Overridable Target Macro Definitions
#
FORCE_REBUILD = force_build
INIT_TARGET = init
PCH_TARGET =
BC_TARGET = 
CODA_TARGET = c:\1218_alibaba\Build\GRANTLEY\RELEASE_MYTOOLS\IA32\AmiModulePkg\TCG2\Common\TcgPei\TrEEPei\DEBUG\TrEEPei.efi \
              

#
# Default target, which will build dependent libraries in addition to source files
#

all: mbuild


#
# Target used when called from platform makefile, which will bypass the build of dependent libraries
#

pbuild: $(INIT_TARGET) $(BC_TARGET) $(PCH_TARGET) $(CODA_TARGET)

#
# ModuleTarget
#

mbuild: $(INIT_TARGET) $(BC_TARGET) gen_libs $(PCH_TARGET) $(CODA_TARGET)

#
# Build Target used in multi-thread build mode, which will bypass the init and gen_libs targets
#

tbuild: $(BC_TARGET) $(PCH_TARGET) $(CODA_TARGET)

#
# Phony target which is used to force executing commands for a target
#
force_build:
	-@

#
# Target to update the FD
#

fds: mbuild gen_fds

#
# Initialization target: print build information and create necessary directories
#
init: info dirs

info:
	-@echo Building ... $(MODULE_DIR)\$(MODULE_FILE) [$(ARCH)]

dirs:
	-@if not exist $(DEBUG_DIR) $(MD) $(DEBUG_DIR)
	-@if not exist $(OUTPUT_DIR) $(MD) $(OUTPUT_DIR)


strdefs:
	-@$(CP) $(DEBUG_DIR)\AutoGen.h $(DEBUG_DIR)\$(MODULE_NAME)StrDefs.h

#
# GenLibsTarget
#
gen_libs:
	@"$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\MdePkg\Library\PeiHobLib\PeiHobLib\Makefile
	@"$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\MdePkg\Library\PeiMemoryAllocationLib\PeiMemoryAllocationLib\Makefile
	@"$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\MdePkg\Library\PeiPcdLib\PeiPcdLib\Makefile
	@"$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\MdePkg\Library\BaseMemoryLibRepStr\BaseMemoryLibRepStr\Makefile
	@"$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\MdePkg\Library\PeiServicesTablePointerLibIdt\PeiServicesTablePointerLibIdt\Makefile
	@"$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\MdePkg\Library\PeiServicesLib\PeiServicesLib\Makefile
	@"$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\AmiModulePkg\Library\PeiAmiDebugLib\PeiAmiDebugLib\Makefile
	@"$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\MdePkg\Library\BaseLib\BaseLib\Makefile
	@"$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\MdePkg\Library\BaseIoLibIntrinsic\BaseIoLibIntrinsic\Makefile
	@"$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\MdePkg\Library\BasePciExpressLib\BasePciExpressLib\Makefile
	@"$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\MdePkg\Library\BasePciLibPciExpress\BasePciLibPciExpress\Makefile
	@"$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\AmiModulePkg\TCG2\ShaLib\TcgHashIntrinsicLib\Makefile
	@"$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\MdePkg\Library\BasePostCodeLibPort80\BasePostCodeLibPort80\Makefile
	@"$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\GrantleyPkg\Library\IntelIchAcpiTimerLib\IntelIchAcpiTimerLib\Makefile
	@"$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\AmiModulePkg\TCG2\ShaLib\ShaLib\Makefile
	@"$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\AmiModulePkg\TCG2\CRB_lib\PttHciLibNull\Makefile
	@"$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\AmiModulePkg\TCG2\CRB_lib\PspfTpmLibNull\Makefile
	@"$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\AmiCompatibilityPkg\Library\AmiPeiLib\Makefile
	@"$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\AmiModulePkg\TCG2\TisLib\TisLib32\Makefile
	@"$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\MdePkg\Library\PeimEntryPoint\PeimEntryPoint\Makefile
	@"$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\AmiModulePkg\TCG2\Common\AmiTcmlib\AmiTcmlib\Makefile
	@"$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\Build\Tpm20CRBLibPei\Makefile
	@"$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\AmiModulePkg\TCG2\Common\AmiTcgPlatformPei\AmiTcgLibPei\Makefile
	@cd $(MODULE_BUILD_DIR)

#
# Build Flash Device Image
#
gen_fds:
	@"$(MAKE)" $(MAKE_FLAGS) -f $(BUILD_DIR)\Makefile fds
	@cd $(MODULE_BUILD_DIR)

#
# Individual Object Build Targets
#
$(DEBUG_DIR)\TrEEPei.efi : $(DEBUG_DIR)\TrEEPei.dll
	"$(GENFW)" -e $(MODULE_TYPE) -o c:\1218_alibaba\Build\GRANTLEY\RELEASE_MYTOOLS\IA32\AmiModulePkg\TCG2\Common\TcgPei\TrEEPei\DEBUG\TrEEPei.efi c:\1218_alibaba\Build\GRANTLEY\RELEASE_MYTOOLS\IA32\AmiModulePkg\TCG2\Common\TcgPei\TrEEPei\DEBUG\TrEEPei.dll $(GENFW_FLAGS)
	$(CP) c:\1218_alibaba\Build\GRANTLEY\RELEASE_MYTOOLS\IA32\AmiModulePkg\TCG2\Common\TcgPei\TrEEPei\DEBUG\TrEEPei.efi $(OUTPUT_DIR)
	$(CP) c:\1218_alibaba\Build\GRANTLEY\RELEASE_MYTOOLS\IA32\AmiModulePkg\TCG2\Common\TcgPei\TrEEPei\DEBUG\TrEEPei.efi $(BIN_DIR)
	-$(CP) $(DEBUG_DIR)\*.map $(OUTPUT_DIR)
	-$(CP) $(DEBUG_DIR)\*.pdb $(OUTPUT_DIR)

$(OUTPUT_DIR)\TrEEPei.lib : $(OBJECT_FILES)
	"$(SLINK)" $(SLINK_FLAGS) /OUT:c:\1218_alibaba\Build\GRANTLEY\RELEASE_MYTOOLS\IA32\AmiModulePkg\TCG2\Common\TcgPei\TrEEPei\OUTPUT\TrEEPei.lib @$(OBJECT_FILES_LIST)

$(DEBUG_DIR)\TrEEPei.dll : $(MAKE_FILE)
$(DEBUG_DIR)\TrEEPei.dll : $(STATIC_LIBRARY_FILES)
	"$(DLINK)" /OUT:c:\1218_alibaba\Build\GRANTLEY\RELEASE_MYTOOLS\IA32\AmiModulePkg\TCG2\Common\TcgPei\TrEEPei\DEBUG\TrEEPei.dll $(DLINK_FLAGS) $(DLINK_SPATH) @$(STATIC_LIBRARY_FILES_LIST)

$(OUTPUT_DIR)\TrEEPei.obj : $(MAKE_FILE)
$(OUTPUT_DIR)\TrEEPei.obj : $(COMMON_DEPS)
$(OUTPUT_DIR)\TrEEPei.obj : $(WORKSPACE)\AmiModulePkg\TCG2\Common\TcgPei\TrEEPei.c
	"$(CC)" /Foc:\1218_alibaba\Build\GRANTLEY\RELEASE_MYTOOLS\IA32\AmiModulePkg\TCG2\Common\TcgPei\TrEEPei\OUTPUT\.\TrEEPei.obj $(CC_FLAGS) -DPEI_BUILD $(INC) c:\1218_alibaba\AmiModulePkg\TCG2\Common\TcgPei\TrEEPei.c

$(OUTPUT_DIR)\AutoGen.obj : $(MAKE_FILE)
$(OUTPUT_DIR)\AutoGen.obj : $(WORKSPACE)\MdePkg\Include\Ppi\CpuIo.h
$(OUTPUT_DIR)\AutoGen.obj : $(WORKSPACE)\MdePkg\Include\Uefi\UefiBaseType.h
$(OUTPUT_DIR)\AutoGen.obj : $(WORKSPACE)\MdePkg\Include\Uefi\UefiMultiPhase.h
$(OUTPUT_DIR)\AutoGen.obj : $(WORKSPACE)\MdePkg\Include\Pi\PiFirmwareVolume.h
$(OUTPUT_DIR)\AutoGen.obj : $(WORKSPACE)\MdePkg\Include\Library\PeimEntryPoint.h
$(OUTPUT_DIR)\AutoGen.obj : $(WORKSPACE)\MdePkg\Include\Pi\PiStatusCode.h
$(OUTPUT_DIR)\AutoGen.obj : $(WORKSPACE)\MdePkg\Include\Library\DebugLib.h
$(OUTPUT_DIR)\AutoGen.obj : $(WORKSPACE)\MdePkg\Include\Ppi\PciCfg2.h
$(OUTPUT_DIR)\AutoGen.obj : $(WORKSPACE)\MdePkg\Include\PiPei.h
$(OUTPUT_DIR)\AutoGen.obj : $(WORKSPACE)\MdePkg\Include\Pi\PiMultiPhase.h
$(OUTPUT_DIR)\AutoGen.obj : $(WORKSPACE)\MdePkg\Include\Pi\PiHob.h
$(OUTPUT_DIR)\AutoGen.obj : $(WORKSPACE)\MdePkg\Include\IndustryStandard\PeImage.h
$(OUTPUT_DIR)\AutoGen.obj : $(WORKSPACE)\MdePkg\Include\Protocol\DebugSupport.h
$(OUTPUT_DIR)\AutoGen.obj : $(WORKSPACE)\MdePkg\Include\Library\BaseLib.h
$(OUTPUT_DIR)\AutoGen.obj : $(DEBUG_DIR)\AutoGen.h
$(OUTPUT_DIR)\AutoGen.obj : $(WORKSPACE)\MdePkg\Include\Pi\PiPeiCis.h
$(OUTPUT_DIR)\AutoGen.obj : $(WORKSPACE)\MdePkg\Include\Pi\PiDependency.h
$(OUTPUT_DIR)\AutoGen.obj : $(WORKSPACE)\MdePkg\Include\Pi\PiS3BootScript.h
$(OUTPUT_DIR)\AutoGen.obj : $(WORKSPACE)\MdePkg\Include\Pi\PiBootMode.h
$(OUTPUT_DIR)\AutoGen.obj : $(WORKSPACE)\MdePkg\Include\Pi\PiFirmwareFile.h
$(OUTPUT_DIR)\AutoGen.obj : $(WORKSPACE)\MdePkg\Include\Guid\WinCertificate.h
$(OUTPUT_DIR)\AutoGen.obj : $(WORKSPACE)\MdePkg\Include\Base.h
$(OUTPUT_DIR)\AutoGen.obj : $(WORKSPACE)\MdePkg\Include\Ia32\ProcessorBind.h
$(OUTPUT_DIR)\AutoGen.obj : $(DEBUG_DIR)\AutoGen.c
	"$(CC)" /Foc:\1218_alibaba\Build\GRANTLEY\RELEASE_MYTOOLS\IA32\AmiModulePkg\TCG2\Common\TcgPei\TrEEPei\OUTPUT\.\AutoGen.obj $(CC_FLAGS) -DPEI_BUILD $(INC) c:\1218_alibaba\Build\GRANTLEY\RELEASE_MYTOOLS\IA32\AmiModulePkg\TCG2\Common\TcgPei\TrEEPei\DEBUG\AutoGen.c



#
# clean all intermediate files
#
clean:
	if exist $(OUTPUT_DIR) $(RD) $(OUTPUT_DIR)
	

#
# clean all generated files
#
cleanall:
	if exist $(DEBUG_DIR) $(RD) $(DEBUG_DIR)
	if exist $(OUTPUT_DIR) $(RD) $(OUTPUT_DIR)
	$(RM) *.pdb *.idb > NUL 2>&1
	$(RM) $(BIN_DIR)\$(MODULE_NAME).efi

#
# clean all dependent libraries built
#
cleanlib:
	-@if exist $(BIN_DIR)\MdePkg\Library\PeiHobLib\PeiHobLib\Makefile "$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\MdePkg\Library\PeiHobLib\PeiHobLib\Makefile cleanall
	-@if exist $(BIN_DIR)\MdePkg\Library\PeiMemoryAllocationLib\PeiMemoryAllocationLib\Makefile "$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\MdePkg\Library\PeiMemoryAllocationLib\PeiMemoryAllocationLib\Makefile cleanall
	-@if exist $(BIN_DIR)\MdePkg\Library\PeiPcdLib\PeiPcdLib\Makefile "$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\MdePkg\Library\PeiPcdLib\PeiPcdLib\Makefile cleanall
	-@if exist $(BIN_DIR)\MdePkg\Library\BaseMemoryLibRepStr\BaseMemoryLibRepStr\Makefile "$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\MdePkg\Library\BaseMemoryLibRepStr\BaseMemoryLibRepStr\Makefile cleanall
	-@if exist $(BIN_DIR)\MdePkg\Library\PeiServicesTablePointerLibIdt\PeiServicesTablePointerLibIdt\Makefile "$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\MdePkg\Library\PeiServicesTablePointerLibIdt\PeiServicesTablePointerLibIdt\Makefile cleanall
	-@if exist $(BIN_DIR)\MdePkg\Library\PeiServicesLib\PeiServicesLib\Makefile "$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\MdePkg\Library\PeiServicesLib\PeiServicesLib\Makefile cleanall
	-@if exist $(BIN_DIR)\AmiModulePkg\Library\PeiAmiDebugLib\PeiAmiDebugLib\Makefile "$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\AmiModulePkg\Library\PeiAmiDebugLib\PeiAmiDebugLib\Makefile cleanall
	-@if exist $(BIN_DIR)\MdePkg\Library\BaseLib\BaseLib\Makefile "$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\MdePkg\Library\BaseLib\BaseLib\Makefile cleanall
	-@if exist $(BIN_DIR)\MdePkg\Library\BaseIoLibIntrinsic\BaseIoLibIntrinsic\Makefile "$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\MdePkg\Library\BaseIoLibIntrinsic\BaseIoLibIntrinsic\Makefile cleanall
	-@if exist $(BIN_DIR)\MdePkg\Library\BasePciExpressLib\BasePciExpressLib\Makefile "$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\MdePkg\Library\BasePciExpressLib\BasePciExpressLib\Makefile cleanall
	-@if exist $(BIN_DIR)\MdePkg\Library\BasePciLibPciExpress\BasePciLibPciExpress\Makefile "$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\MdePkg\Library\BasePciLibPciExpress\BasePciLibPciExpress\Makefile cleanall
	-@if exist $(BIN_DIR)\AmiModulePkg\TCG2\ShaLib\TcgHashIntrinsicLib\Makefile "$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\AmiModulePkg\TCG2\ShaLib\TcgHashIntrinsicLib\Makefile cleanall
	-@if exist $(BIN_DIR)\MdePkg\Library\BasePostCodeLibPort80\BasePostCodeLibPort80\Makefile "$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\MdePkg\Library\BasePostCodeLibPort80\BasePostCodeLibPort80\Makefile cleanall
	-@if exist $(BIN_DIR)\GrantleyPkg\Library\IntelIchAcpiTimerLib\IntelIchAcpiTimerLib\Makefile "$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\GrantleyPkg\Library\IntelIchAcpiTimerLib\IntelIchAcpiTimerLib\Makefile cleanall
	-@if exist $(BIN_DIR)\AmiModulePkg\TCG2\ShaLib\ShaLib\Makefile "$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\AmiModulePkg\TCG2\ShaLib\ShaLib\Makefile cleanall
	-@if exist $(BIN_DIR)\AmiModulePkg\TCG2\CRB_lib\PttHciLibNull\Makefile "$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\AmiModulePkg\TCG2\CRB_lib\PttHciLibNull\Makefile cleanall
	-@if exist $(BIN_DIR)\AmiModulePkg\TCG2\CRB_lib\PspfTpmLibNull\Makefile "$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\AmiModulePkg\TCG2\CRB_lib\PspfTpmLibNull\Makefile cleanall
	-@if exist $(BIN_DIR)\AmiCompatibilityPkg\Library\AmiPeiLib\Makefile "$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\AmiCompatibilityPkg\Library\AmiPeiLib\Makefile cleanall
	-@if exist $(BIN_DIR)\AmiModulePkg\TCG2\TisLib\TisLib32\Makefile "$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\AmiModulePkg\TCG2\TisLib\TisLib32\Makefile cleanall
	-@if exist $(BIN_DIR)\MdePkg\Library\PeimEntryPoint\PeimEntryPoint\Makefile "$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\MdePkg\Library\PeimEntryPoint\PeimEntryPoint\Makefile cleanall
	-@if exist $(BIN_DIR)\AmiModulePkg\TCG2\Common\AmiTcmlib\AmiTcmlib\Makefile "$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\AmiModulePkg\TCG2\Common\AmiTcmlib\AmiTcmlib\Makefile cleanall
	-@if exist $(BIN_DIR)\Build\Tpm20CRBLibPei\Makefile "$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\Build\Tpm20CRBLibPei\Makefile cleanall
	-@if exist $(BIN_DIR)\AmiModulePkg\TCG2\Common\AmiTcgPlatformPei\AmiTcgLibPei\Makefile "$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\AmiModulePkg\TCG2\Common\AmiTcgPlatformPei\AmiTcgLibPei\Makefile cleanall
	@cd $(MODULE_BUILD_DIR)

