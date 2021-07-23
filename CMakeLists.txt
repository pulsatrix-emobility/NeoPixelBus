idf_component_register(
        SRCS
        src/internal/Esp32_i2s.c
        src/internal/NeoPixelAvr.c
        src/internal/NeoGamma.cpp
        src/internal/SegmentDigit.cpp
        src/internal/HtmlColorShortNames.cpp
        src/internal/HsbColor.cpp
        src/internal/NeoEspBitBangMethod.cpp
        src/internal/NeoEsp8266DmaMethod.cpp
        src/internal/RgbwColor.cpp
        src/internal/RgbColorBase.cpp
        src/internal/HtmlColorNames.cpp
        src/internal/NeoPixelAnimator.cpp
        src/internal/HtmlColorNameStrings.cpp
        src/internal/HtmlColor.cpp
        src/internal/NeoEsp8266UartMethod.cpp
        src/internal/RgbColor.cpp
        src/internal/HslColor.cpp
        src/internal/NeoEsp32RmtMethod.cpp
        src/internal/Rgb48Color.cpp

        INCLUDE_DIRS "src"
        REQUIRES arduino
)
