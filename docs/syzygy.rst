Syzygy endgame tablebase probing
================================

Syzygy tablebases provide **WDL** (win/draw/loss) and **DTZ** (distance to
zero) information for all endgame positions with up to 7 pieces.
Positions with castling rights are not included.

.. warning::
    Ensure tablebase files match the known checksums. Maliciously crafted
    tablebase files may cause denial of service.

.. autofunction:: chess.syzygy.open_tablebase

.. autoclass:: chess.syzygy.Tablebase
    :members:
