idf_component_register(
        SRCS
        src/internal/animations/NeoPixelAnimator.cpp
        src/internal/colors/HsbColor.cpp
        src/internal/colors/HslColor.cpp
        src/internal/colors/HtmlColor.cpp
        src/internal/colors/HtmlColorNames.cpp
        src/internal/colors/HtmlColorNameStrings.cpp
        src/internal/colors/HtmlColorShortNames.cpp
        src/internal/colors/NeoGammaDynamicTableMethod.cpp
        src/internal/colors/NeoGammaTableMethod.cpp
        src/internal/colors/Rgb48Color.cpp
        src/internal/colors/RgbColor.cpp
        src/internal/colors/RgbColorBase.cpp
        src/internal/colors/Rgbw64Color.cpp
        src/internal/colors/RgbwColor.cpp
        src/internal/colors/Rgbww80Color.cpp
        src/internal/colors/RgbwwColor.cpp
        src/internal/colors/RgbwwwColor.cpp
        src/internal/colors/SegmentDigit.cpp
        src/internal/methods/Esp32_i2s.c
        # src/internal/methods/NeoEsp32RmtMethod.cpp # not used by us
        src/internal/methods/NeoEsp8266I2sMethodCore.cpp
        # src/internal/methods/NeoEsp8266UartMethod.cpp # not used by us
        # src/internal/methods/NeoEspBitBangMethod.cpp # not used by us
        src/internal/methods/NeoPixelAvr.c
        
        INCLUDE_DIRS "src"
        REQUIRES arduino
)
