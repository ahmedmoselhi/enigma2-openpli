installdir = $(pkglibdir)/python/Plugins/SystemPlugins

SUBDIRS = SoftwareManager PositionerSetup Satfinder \
	SatelliteEquipmentControl Videomode VideoTune Hotplug \
	DefaultServicesScanner DiseqcTester CommonInterfaceAssignment \
	CableScan FastScan OSDPositionSetup OSD3DSetup HdmiCEC VideoClippingSetup \
	VideoEnhancement WirelessLan NetworkWizard \
	VFD-Icons SH4BoosterControl SH4OSDAdjustment WirelessLan

if ENABLE_SPARK7162
SUBDIRS += SparkUnionTunerType
endif

install_PYTHON =	\
	__init__.py
