set(SOURCES PVRChannelNumberInputHandler.cpp
            PVRContextMenus.cpp
            PVRDatabase.cpp
            PVREventLogJob.cpp
            PVRItem.cpp
            PVRManager.cpp
            PVRPlaybackState.cpp
            PVRStreamProperties.cpp
            PVRThumbLoader.cpp)

set(HEADERS PVRChannelNumberInputHandler.h
            PVRContextMenus.h
            PVRDatabase.h
            PVREventLogJob.h
            PVRItem.h
            PVRManager.h
            PVRPlaybackState.h
            PVRStreamProperties.h
            PVRThumbLoader.h)

core_add_library(pvr)
