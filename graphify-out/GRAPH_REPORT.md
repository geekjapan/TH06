# Graph Report - TH06  (2026-10-23)

## Corpus Check
- 12 semantic source files; AST status: extracted. Exclusions and reuse evidence: build-audit.json.

## Summary
- 3847 nodes · 6424 edges · 222 communities (158 shown, 64 thin omitted)
- Extraction: 98% EXTRACTED · 2% INFERRED · 0% AMBIGUOUS · INFERRED: 141 edges (avg confidence: 0.85)
- Token usage: per-project usage unavailable (native Codex semantic extraction).

## Graph Freshness
- Built from commit: `cc475a0b`
- Run `git rev-parse HEAD` and compare to check if the graph is stale.
- Run `graphify update .` after code changes (no API cost).

## Community Hubs (Navigation)
- EclRawInstrOpcode
- PE
- EnemyEclInstr.cpp
- Enemy
- GameManager
- MainMenu
- pefile.py
- Structure
- Supervisor
- FileAbstraction
- Player
- TextHelper
- Effect
- ResultScreen
- AnmVm
- PrologEpilogOp
- AnmManager
- Ending
- SoundPlayer
- MidiOpcode
- Pbg3Archive
- create_devenv.py
- GameWindow
- Item
- Gui
- Stage
- Gui.cpp
- SoundIdx
- Player.cpp
- MidiOutput
- StructureWithBitfields
- MidiOutput.cpp
- argparse
- GameConfiguration
- EclRawInstrArgs
- VertexTex1DiffuseXyz
- Writer
- ScreenEffect
- Laser
- CharacterPowerBulletData
- SectionStructure
- ZunResult
- AnmRawEntry
- Bullet
- BulletManager
- TouhouButton
- debug.py
- GameErrorContext
- .dump_info
- AsciiManager
- EnemyLaserShooter
- MusicRoom
- IPbg3Parser
- ReplayManager
- sys
- f32
- CWaveFile
- ParticleEffects
- EnemyBulletShooter
- MidiTimer
- PlayerBullet
- i32
- EnemyManager
- GuiImpl
- MidiTrack
- StageReplayData
- ZunTimer
- AsciiManager.cpp
- MsgRawInstrArgs
- GameState
- ResultScreenState
- AsciiManagerPopup
- EndOpcode
- EnemyEclContext
- EnemyFlags
- generate_function_decompme.py
- ExportDecomp.java
- Chain
- PlayerBombInfo
- ReplayData
- EclManager.hpp
- zwave.cpp
- SymbolTable
- UnicodeStringWrapperPostProcessor
- ChainCallbackResult
- ChainElem
- ghidra.app.script.GhidraScript
- MidiDevice
- BombData.cpp
- EclRawInstrLaserArgs
- GuiMsgVm
- MsgOps
- Rng
- GenerateMapping.java
- Dump
- EclRawInstrArg
- Th6k
- RawStageQuadBasic
- PEFormatError
- AnmLoadedSprite
- AnmVmFlagsEnum
- ZunVec3
- Hscr
- GameConfigOptsShifts
- ImportFromXml.java
- subprocess
- StringTable
- pragma_var_order.cpp
- ParserCtx
- Controller.cpp
- Pscr
- SupervisorState
- .SpawnSingleBullet
- EclManager
- AuxRecordBfEf
- LineNumber
- BulletTypeSprites
- Detouring
- EclTimelineInstr
- EclRawInstrAnmSetPosesArgs
- EclTimelineInstrArgs
- EnemyManager.cpp
- Catk
- StageMenu
- coff.py
- ExtractIcon
- BulletAimMode
- EclRawInstrBulletArgs
- OptionsCursorPosition
- PlayerDirection
- CSound
- Scope
- EclRawInstrBulletEffectsArgs
- RunningSpellcardInfo
- GuiFormattedText
- MsgRawInstr
- ScoreDat
- RawStageHeader
- CStreamingSound
- update_decompile_stats.py
- file
- CSoundManager
- set_bitfields_format
- Unprotector
- HashNode
- .DrawInner
- AnmRawInstr
- UpdateGameMenuState
- StageNumber
- ResultScreenMainMenuCursor
- RawStageObject
- DWORD
- Token
- .unpack
- Entry
- TokenStream
- BulletState
- EclRawInstrBulletRankInfluenceArgs
- GuiFlags
- StageOpcode
- ghidra.framework.model.DomainObject
- .adjust_SectionAlignment
- RetryGameMenuState
- EclRawInstrCallArgs
- EclRawInstrEnemyCreateArgs
- Difficulty
- OrbState
- RawStageInstr
- AuxRecordFunctionDef
- AddressSet
- PrologEpilogOpAllocLarge
- AnmVmAnchor
- EclRawInstrAnmSetDeathArgs
- TrackDescriptor
- BulletType
- PlayerState
- ZunRect
- StageCameraSky
- AuxRecordRaw
- WeirdPadding
- EclRawInstrJumpArgs
- CursorMovement
- SpellcardState
- AnmVmBlendMode
- AnmVmColorOp
- EclRawInstrMoveBoundSetArgs
- EffectCallbackResult
- TH06 decorated symbols
- Cached Windows toolchain
- Ghidra object comparison
- Cosign signing
- th06-re
- Ghidra mapping pull request
- clang-format and Ruff
- Touhou 1.02h and objdiff
- Blonde red-eyed anime face
- Implementation progress graphic
- Progress display: anime portrait with 97.65 percent completion bar and 97.51 percent accuracy text
- Progress template with FUNC_PROG_PERCENT percentage placeholder in bottom white bar

## God Nodes (most connected - your core abstractions)
1. `EclRawInstrOpcode` - 137 edges
2. `Enemy` - 96 edges
3. `Player` - 96 edges
4. `PE` - 94 edges
5. `AnmVm` - 87 edges
6. `ZunResult` - 82 edges
7. `AnmManager` - 81 edges
8. `GameManager` - 81 edges
9. `Supervisor` - 77 edges
10. `MainMenu` - 67 edges

## Surprising Connections (you probably didn't know these)
- `configure()` --uses--> `Writer`  [INFERRED]
  scripts/configure.py → scripts/ninja_syntax.py
- `CheckForRunningGameInstance()` --references--> `ZunResult`  [EXTRACTED]
  src/utils.cpp → src/ZunResult.hpp
- `build()` --calls--> `run_windows_program()`  [INFERRED]
  scripts/build.py → scripts/winhelpers.py
- `install_python()` --calls--> `run_windows_program()`  [INFERRED]
  scripts/create_devenv.py → scripts/winhelpers.py
- `main()` --calls--> `run_windows_program()`  [INFERRED]
  scripts/create_devenv.py → scripts/winhelpers.py

## Import Cycles
- None detected.

## Communities (222 total, 64 thin omitted)

### Community 0 - "EclRawInstrOpcode"
Cohesion: 0.01
Nodes (137): EclRawInstrOpcode, ECL_OPCODE_ANMFLAGROTATION, ECL_OPCODE_ANMINTERRUPTMAIN, ECL_OPCODE_ANMINTERRUPTSLOT, ECL_OPCODE_ANMSETDEATH, ECL_OPCODE_ANMSETMAIN, ECL_OPCODE_ANMSETPOSES, ECL_OPCODE_ANMSETSLOT (+129 more)

### Community 2 - "EnemyEclInstr.cpp"
Cohesion: 0.05
Nodes (74): EclRawInstr, args, offsetToNext, opCode, skipForDifficulty, time, unk_8, unk_a (+66 more)

### Community 3 - "Enemy"
Cohesion: 0.03
Nodes (63): Enemy, acceleration, angle, angularVelocity, anmExDefaults, anmExFarLeft, anmExFarRight, anmExFlags (+55 more)

### Community 4 - "GameManager"
Cohesion: 0.03
Nodes (55): GameManager, arcadeRegionSize, arcadeRegionTopLeftPos, bombsRemaining, bombsUsed, cameraDistance, catk, character (+47 more)

### Community 5 - "MainMenu"
Cohesion: 0.03
Nodes (36): MainMenu, chainCalc, chainDraw, chosenReplay, color1, color2, colorMode16bit, controlMapping (+28 more)

### Community 6 - "pefile.py"
Cohesion: 0.05
Nodes (23): BaseRelocationData, BddDynamicRelocationData, BoundImportDescData, BoundImportRefData, DataContainer, DebugData, DynamicRelocationData, ExceptionsDirEntryData (+15 more)

### Community 7 - "Structure"
Cohesion: 0.08
Nodes (5): ImportDescData, is_valid_dos_filename(), is_valid_function_name(), length_until_eof(), Structure

### Community 8 - "Supervisor"
Cohesion: 0.04
Nodes (35): Supervisor, calcCount, cfg, colorMode16Bits, controller, controllerCaps, curState, d3dCaps (+27 more)

### Community 9 - "FileAbstraction"
Cohesion: 0.08
Nodes (5): FileAbstraction, access, handle, IFileAbstraction, Pbg3Parser

### Community 10 - "Player"
Cohesion: 0.04
Nodes (43): Player, bombInfo, bombProjectiles, bombRegionDamages, bombRegionPositions, bombRegionSizes, bulletGracePeriod, bullets (+35 more)

### Community 11 - "TextHelper"
Cohesion: 0.06
Nodes (25): A1R5G5B5, alpha, blue, green, red, FormatInfo, alphaMask, bitCount (+17 more)

### Community 12 - "Effect"
Cohesion: 0.07
Nodes (24): Effect, angleRelated, effectId, inUseFlag, pos1, pos2, position, quaternion (+16 more)

### Community 13 - "ResultScreen"
Cohesion: 0.04
Nodes (27): ResultScreen, calcChain, charUsed, cheatCodeStep, cursor, defaultReplay, defaultScore, diffSelected (+19 more)

### Community 14 - "AnmVm"
Cohesion: 0.04
Nodes (39): AnmVm, activeSpriteIndex, alphaInterpEndTime, alphaInterpFinal, alphaInterpInitial, alphaInterpTime, angleVel, anmFileIndex (+31 more)

### Community 15 - "PrologEpilogOp"
Cohesion: 0.05
Nodes (10): PrologEpilogOp, PrologEpilogOpAllocSmall, PrologEpilogOpEpilogMarker, PrologEpilogOpPushFrame, PrologEpilogOpPushReg, PrologEpilogOpSaveReg, PrologEpilogOpSaveRegFar, PrologEpilogOpSaveXMM (+2 more)

### Community 16 - "AnmManager"
Cohesion: 0.05
Nodes (27): AnmManager, anmFiles, anmFilesSpriteIndexOffsets, currentBlendMode, currentColorOp, currentSprite, currentTexture, currentTextureFactor (+19 more)

### Community 17 - "Ending"
Cohesion: 0.05
Nodes (29): Ending, backgroundPos, backgroundScrollSpeed, calcChain, drawChain, endFileData, endFileDataPtr, endingFadeColor (+21 more)

### Community 18 - "SoundPlayer"
Cohesion: 0.05
Nodes (20): SoundBufferIdxVolume, bufferIdx, unk, volume, SoundPlayer, backgroundMusic, backgroundMusicThreadHandle, backgroundMusicThreadId (+12 more)

### Community 19 - "MidiOpcode"
Cohesion: 0.05
Nodes (39): MidiOpcode, MIDI_OPCODE_ACTIVE_SENSING, MIDI_OPCODE_CHANNEL_1, MIDI_OPCODE_CHANNEL_2, MIDI_OPCODE_CHANNEL_3, MIDI_OPCODE_CHANNEL_4, MIDI_OPCODE_CHANNEL_5, MIDI_OPCODE_CHANNEL_6 (+31 more)

### Community 20 - "Pbg3Archive"
Cohesion: 0.10
Nodes (16): Pbg3Archive, entries, fileTableOffset, numOfEntries, parser, unk, Pbg3Entry, checksum (+8 more)

### Community 21 - "create_devenv.py"
Cohesion: 0.10
Nodes (27): check_file(), cmd_quote(), copytree_exist_ok(), download_requirement(), download_requirement_torrent(), download_requirements(), file_matches(), get_sha256() (+19 more)

### Community 22 - "GameWindow"
Cohesion: 0.06
Nodes (15): Direct3DCreate8(), GameWindow, curFrame, isAppActive, isAppClosing, lastActiveAppValue, lowPowerActive, powerOffActive (+7 more)

### Community 23 - "Item"
Cohesion: 0.06
Nodes (27): EclRawInstrDropItemArgs, itemId, calculatePointScore(), Item, currentPosition, isInUse, itemType, sprite (+19 more)

### Community 24 - "Gui"
Cohesion: 0.07
Nodes (10): Gui, blueSpellcardBarLength, bombSpellcardBarLength, bossHealthBar1, bossHealthBar2, bossUIOpacity, eclSetLives, flags (+2 more)

### Community 25 - "Stage"
Cohesion: 0.05
Nodes (32): Stage, beginningOfScript, facingDirInterpDuration, facingDirInterpFinal, facingDirInterpInitial, facingDirInterpTimer, instructionIndex, objectInstances (+24 more)

### Community 26 - "Gui.cpp"
Cohesion: 0.12
Nodes (3): FileSystem::OpenPath(), DIFFABLE_STATIC_ARRAY_ASSIGN(), DIFFABLE_STATIC_ARRAY_ASSIGN()

### Community 27 - "SoundIdx"
Cohesion: 0.06
Nodes (36): EclRawInstrBulletSoundArgs, bulletSfx, SoundIdx, NO_SOUND, SOUND_1, SOUND_12, SOUND_15, SOUND_16 (+28 more)

### Community 28 - "Player.cpp"
Cohesion: 0.07
Nodes (21): EnemyBulletShooter, EnemyLaserShooter, DIFFABLE_STATIC_ARRAY_ASSIGN(), Character, CHARA_MARISA, CHARA_REIMU, PlayerBulletState, PLAYER_BULLET_STATE_COLLIDED (+13 more)

### Community 29 - "MidiOutput"
Cohesion: 0.06
Nodes (28): MidiOutput, channels, divisions, fadeOutElapsedMS, fadeOutFlag, fadeOutInterval, fadeOutLastSetVolume, fadeOutVolumeMultiplier (+20 more)

### Community 30 - "StructureWithBitfields"
Cohesion: 0.09
Nodes (3): PrologEpilogOpsFactory, StructureWithBitfields, UnwindInfo

### Community 31 - "MidiOutput.cpp"
Cohesion: 0.11
Nodes (6): DIFFABLE_STATIC_ARRAY_ASSIGN(), StageFile, anmFile, stdFile, AddNormalizeAngle(), CheckForRunningGameInstance()

### Community 32 - "argparse"
Cohesion: 0.17
Nodes (11): export(), fetchVersions(), getLatestVersionInRepo(), main(), parseUserMappings(), main(), main(), findAnalyzeHeadless() (+3 more)

### Community 33 - "GameConfiguration"
Cohesion: 0.07
Nodes (25): ControllerMapping, bombButton, downButton, focusButton, leftButton, menuButton, rightButton, shootButton (+17 more)

### Community 34 - "EclRawInstrArgs"
Cohesion: 0.07
Nodes (27): EclRawInstrArgs, alu, anmInterruptSlot, anmSetDeath, anmSetMain, anmSetPoses, anmSetSlot, bullet (+19 more)

### Community 35 - "VertexTex1DiffuseXyz"
Cohesion: 0.09
Nodes (21): AnmRawSprite, id, offset, size, RenderVertexInfo, position, textureUV, VertexDiffuseXyzrwh (+13 more)

### Community 36 - "Writer"
Cohesion: 0.12
Nodes (5): as_list(), escape(), escape_path(), expand(), Writer

### Community 38 - "ScreenEffect"
Cohesion: 0.13
Nodes (11): ScreenEffect, calcChainElement, drawChainElement, effectLength, fadeAlpha, genericParam, shakinessParam, timer (+3 more)

### Community 39 - "Laser"
Cohesion: 0.08
Nodes (20): Laser, angle, color, despawnDuration, duration, endOffset, flags, hitboxEndDelay (+12 more)

### Community 40 - "CharacterPowerBulletData"
Cohesion: 0.09
Nodes (15): CharacterPowerBulletData, anmFileIdx, bulletFrame, bulletSoundIdx, bulletType, damage, direction, motion (+7 more)

### Community 42 - "ZunResult"
Cohesion: 0.11
Nodes (5): ZunAlloc(), ZunFree(), ZunResult, ZUN_ERROR, ZUN_SUCCESS

### Community 44 - "AnmRawEntry"
Cohesion: 0.09
Nodes (22): AnmRawEntry, colorKey, format, hasData, height, mipmapNameOffset, nameOffset, nextOffset (+14 more)

### Community 46 - "Bullet"
Cohesion: 0.09
Nodes (23): Bullet, angle, dirChangeInterval, dirChangeMaxTimes, dirChangeNumTimes, dirChangeRotation, dirChangeSpeed, ex4Acceleration (+15 more)

### Community 47 - "BulletManager"
Cohesion: 0.11
Nodes (9): BulletManager, bulletAnmPath, bulletCount, bullets, bulletTypeTemplates, lasers, nextBulletIndex, time (+1 more)

### Community 48 - "TouhouButton"
Cohesion: 0.09
Nodes (23): TouhouButton, TH_BUTTON_ANY, TH_BUTTON_BOMB, TH_BUTTON_DIRECTION, TH_BUTTON_DOWN, TH_BUTTON_DOWN_LEFT, TH_BUTTON_DOWN_RIGHT, TH_BUTTON_ENTER (+15 more)

### Community 49 - "debug.py"
Cohesion: 0.10
Nodes (4): InteractiveSocket, RequestPythonREPL, ThreadAwareStdout, ThreadedTCPServer

### Community 50 - "GameErrorContext"
Cohesion: 0.11
Nodes (6): CMyFont, m_lpFont, GameErrorContext, m_Buffer, m_BufferEnd, m_ShowMessageBox

### Community 51 - ".dump_info"
Cohesion: 0.11
Nodes (4): count_zeroes(), get_sublang_name_for_lang(), retrieve_flags(), set_flags()

### Community 52 - "AsciiManager"
Cohesion: 0.10
Nodes (15): AsciiManager, color, gameMenu, isGui, isSelected, nextPopupIndex1, nextPopupIndex2, numStrings (+7 more)

### Community 53 - "EnemyLaserShooter"
Cohesion: 0.09
Nodes (21): EnemyLaserShooter, angle, despawnDuration, duration, endOffset, flags, hitboxEndDelay, hitboxStartTime (+13 more)

### Community 54 - "MusicRoom"
Cohesion: 0.10
Nodes (13): MusicRoom, calc_chain, cursor, descriptionSprites, draw_chain, enableInput, listingOffset, mainVm (+5 more)

### Community 55 - "IPbg3Parser"
Cohesion: 0.13
Nodes (6): IPbg3Parser, bitIdxInCurByte, crc, curByte, fileSize, offsetInFile

### Community 56 - "ReplayManager"
Cohesion: 0.12
Nodes (11): ReplayManager, calcChain, calcChainDemoHighPrio, drawChain, frameId, replayData, replayFile, replayInputs (+3 more)

### Community 57 - "sys"
Cohesion: 0.20
Nodes (8): main(), generate_function_diff_objdiff(), generate_function_diff_satsuki(), main(), main(), demangle_msvc(), rename_symbols(), sym_prefix()

### Community 58 - "f32"
Cohesion: 0.10
Nodes (15): f32, CharacterData, diagonalMovementSpeed, diagonalMovementSpeedFocus, fireBulletCallback, fireBulletFocusCallback, orthogonalMovementSpeed, orthogonalMovementSpeedFocus (+7 more)

### Community 59 - "CWaveFile"
Cohesion: 0.10
Nodes (14): CWaveFile, m_bIsReadingFromMemory, m_ck, m_ckRiff, m_dwFlags, m_dwSize, m_hmmio, m_loopEndPoint (+6 more)

### Community 60 - "ParticleEffects"
Cohesion: 0.10
Nodes (21): ParticleEffects, PARTICLE_EFFECT_UNK_0, PARTICLE_EFFECT_UNK_1, PARTICLE_EFFECT_UNK_10, PARTICLE_EFFECT_UNK_11, PARTICLE_EFFECT_UNK_12, PARTICLE_EFFECT_UNK_13, PARTICLE_EFFECT_UNK_14 (+13 more)

### Community 61 - "EnemyBulletShooter"
Cohesion: 0.10
Nodes (17): EnemyBulletShooter, aimMode, angle1, angle2, count1, count2, exFloats, exInts (+9 more)

### Community 62 - "MidiTimer"
Cohesion: 0.13
Nodes (6): MidiShortMsg, dwMsg, msg, MidiTimer, timeCaps, timerId

### Community 63 - "PlayerBullet"
Cohesion: 0.13
Nodes (13): PlayerBullet, bulletState, bulletType, damage, position, sidewaysMotion, size, spawnPositionIdx (+5 more)

### Community 64 - "i32"
Cohesion: 0.10
Nodes (17): EclRawInstrAnmInterruptSlotArgs, interruptId, vmId, EclRawInstrAnmSetMainArgs, scriptIdx, EclRawInstrAnmSetSlotArgs, scriptIdx, vmIdx (+9 more)

### Community 65 - "EnemyManager"
Cohesion: 0.10
Nodes (14): EnemyManager, bosses, enemies, enemyCount, enemyTemplate, randomItemSpawnIndex, randomItemTableIndex, spellcardInfo (+6 more)

### Community 66 - "GuiImpl"
Cohesion: 0.10
Nodes (18): GuiImpl, bombSpellcardBackground, bombSpellcardName, bonusScore, bossHealthBarState, enemySpellcardBackground, enemySpellcardName, enemySpellcardPortrait (+10 more)

### Community 67 - "MidiTrack"
Cohesion: 0.10
Nodes (18): MidiChannel, channelVolume, effectOneDepth, effectThreeDepth, instrument, instrumentBank, keyPressedFlags, modifiedVolume (+10 more)

### Community 68 - "StageReplayData"
Cohesion: 0.11
Nodes (15): ReplayDataInput, frameNum, inputKey, padding, StageReplayData, bombsRemaining, livesRemaining, padding (+7 more)

### Community 69 - "ZunTimer"
Cohesion: 0.17
Nodes (4): ZunTimer, current, previous, subFrame

### Community 71 - "MsgRawInstrArgs"
Cohesion: 0.12
Nodes (17): MsgRawInstrArgAnmInterrupt, unk1, unk2, MsgRawInstrArgPortraitAnmScript, anmScriptIdx, portraitIdx, MsgRawInstrArgs, anmInterrupt (+9 more)

### Community 72 - "GameState"
Cohesion: 0.11
Nodes (19): GameState, STATE_CHARACTER_LOAD, STATE_CHARACTER_SELECT, STATE_DIFFICULTY_LOAD, STATE_DIFFICULTY_SELECT, STATE_KEYCONFIG, STATE_MAIN_MENU, STATE_MUSIC_ROOM (+11 more)

### Community 73 - "ResultScreenState"
Cohesion: 0.11
Nodes (19): ResultScreenState, RESULT_SCREEN_STATE_BEST_SCORES_EASY, RESULT_SCREEN_STATE_BEST_SCORES_EXTRA, RESULT_SCREEN_STATE_BEST_SCORES_HARD, RESULT_SCREEN_STATE_BEST_SCORES_LUNATIC, RESULT_SCREEN_STATE_BEST_SCORES_NORMAL, RESULT_SCREEN_STATE_CANT_SAVE_REPLAY, RESULT_SCREEN_STATE_CHOOSING_DIFFICULTY (+11 more)

### Community 74 - "AsciiManagerPopup"
Cohesion: 0.12
Nodes (14): AsciiManagerPopup, characterCount, color, digits, inUse, position, timer, AsciiManagerString (+6 more)

### Community 75 - "EndOpcode"
Cohesion: 0.11
Nodes (18): EndOpcode, END_OPCODE_BACKGROUND, END_OPCODE_COLOR, END_OPCODE_END, END_OPCODE_EXEC_END_FILE, END_OPCODE_EXECUTE_ANM, END_OPCODE_FADE_IN, END_OPCODE_FADE_IN_BLACK (+10 more)

### Community 76 - "EnemyEclContext"
Cohesion: 0.11
Nodes (17): EnemyEclContext, compareRegister, currentInstr, float0, float1, float2, float3, subId (+9 more)

### Community 77 - "EnemyFlags"
Cohesion: 0.11
Nodes (17): EnemyFlags, deathMode, disableCallStack, hasBeenInBounds, invertX, isBoss, isCollidable, isDamageable (+9 more)

### Community 78 - "generate_function_decompme.py"
Cohesion: 0.19
Nodes (7): build(), main(), BuildType, configure(), cpp_expand(), cpp_expand_path(), main()

### Community 80 - "Chain"
Cohesion: 0.20
Nodes (6): Chain, calcChain, drawChain, midiOutputDeviceCount, unk, callback

### Community 81 - "PlayerBombInfo"
Cohesion: 0.12
Nodes (13): CharacterPowerData, bullets, numBullets, power, PlayerBombInfo, bombRegionPositions, bombRegionVelocities, duration (+5 more)

### Community 82 - "ReplayData"
Cohesion: 0.12
Nodes (17): ReplayData, checksum, date, difficulty, key, magic, name, rngValue1 (+9 more)

### Community 83 - "EclManager.hpp"
Cohesion: 0.24
Nodes (3): Enemy, EnemyEclContext, EnemyManager

### Community 85 - "SymbolTable"
Cohesion: 0.15
Nodes (3): FileHeader, ObjectModule, SymbolTable

### Community 87 - "ChainCallbackResult"
Cohesion: 0.12
Nodes (8): ChainCallbackResult, CHAIN_CALLBACK_RESULT_BREAK, CHAIN_CALLBACK_RESULT_CONTINUE, CHAIN_CALLBACK_RESULT_CONTINUE_AND_REMOVE_JOB, CHAIN_CALLBACK_RESULT_EXECUTE_AGAIN, CHAIN_CALLBACK_RESULT_EXIT_GAME_ERROR, CHAIN_CALLBACK_RESULT_EXIT_GAME_SUCCESS, CHAIN_CALLBACK_RESULT_RESTART_FROM_FIRST_JOB

### Community 88 - "ChainElem"
Cohesion: 0.15
Nodes (9): ChainElem, addedCallback, arg, deletedCallback, isHeapAllocated, next, prev, priority (+1 more)

### Community 90 - "MidiDevice"
Cohesion: 0.17
Nodes (3): MidiDevice, deviceId, handle

### Community 92 - "EclRawInstrLaserArgs"
Cohesion: 0.13
Nodes (15): EclRawInstrLaserArgs, angle, color, despawnDuration, duration, endOffset, flags, hitboxEndDelay (+7 more)

### Community 93 - "GuiMsgVm"
Cohesion: 0.13
Nodes (14): GuiMsgVm, currentInstr, currentMsgIdx, dialogueLines, dialogueSkippable, fontSize, framesElapsedDuringPause, ignoreWaitCounter (+6 more)

### Community 94 - "MsgOps"
Cohesion: 0.13
Nodes (15): MsgOps, MSG_OPCODE_ANMINTERRUPT, MSG_OPCODE_ECLRESUME, MSG_OPCODE_MSGDELETE, MSG_OPCODE_MSGHALT, MSG_OPCODE_MUSIC, MSG_OPCODE_MUSICFADEOUT, MSG_OPCODE_PORTRAITANMSCRIPT (+7 more)

### Community 96 - "Rng"
Cohesion: 0.23
Nodes (3): Rng, generationCount, seed

### Community 99 - "EclRawInstrArg"
Cohesion: 0.14
Nodes (14): EclRawInstrAluArgs, arg1, arg2, arg3, arg4, res, EclRawInstrArg, by (+6 more)

### Community 100 - "Th6k"
Cohesion: 0.15
Nodes (11): Clrd, base, characterShotType, difficultyClearedWithoutRetries, difficultyClearedWithRetries, Th6k, magic, th6kLen (+3 more)

### Community 101 - "RawStageQuadBasic"
Cohesion: 0.15
Nodes (11): RawStageObjectInstance, id, position, unk2, RawStageQuadBasic, anmScript, byteSize, position (+3 more)

### Community 102 - "PEFormatError"
Cohesion: 0.15
Nodes (3): ExportData, ImportData, PEFormatError

### Community 103 - "AnmLoadedSprite"
Cohesion: 0.15
Nodes (11): AnmLoadedSprite, endPixelInclusive, heightPx, sourceFileIndex, spriteId, startPixelInclusive, textureHeight, textureWidth (+3 more)

### Community 104 - "AnmVmFlagsEnum"
Cohesion: 0.15
Nodes (13): AnmVmFlagsEnum, AnmVmFlags_1, AnmVmFlags_4, AnmVmFlags_AnchorLeft, AnmVmFlags_AnchorTop, AnmVmFlags_BlendMode, AnmVmFlags_ColorOp, AnmVmFlags_FlipX (+5 more)

### Community 105 - "ZunVec3"
Cohesion: 0.15
Nodes (13): EclRawInstrLaserOpArgs, arg1, laserIdx, EclRawInstrMoveArgs, pos, EclRawInstrSpellcardEffectArgs, effectColorId, effectDistance (+5 more)

### Community 106 - "Hscr"
Cohesion: 0.15
Nodes (11): Hscr, base, character, difficulty, name, score, stage, ScoreListNode (+3 more)

### Community 107 - "GameConfigOptsShifts"
Cohesion: 0.15
Nodes (13): GameConfigOptsShifts, GCOS_CLEAR_BACKBUFFER_ON_REFRESH, GCOS_DISPLAY_MINIMUM_GRAPHICS, GCOS_DONT_USE_FOG, GCOS_DONT_USE_VERTEX_BUF, GCOS_FORCE_16BIT_COLOR_MODE, GCOS_FORCE_60FPS, GCOS_NO_COLOR_COMP (+5 more)

### Community 109 - "subprocess"
Cohesion: 0.27
Nodes (6): install_pragma_var_order(), main(), get_windows_path(), run_windows_program(), run_windows_program_output(), wine_env()

### Community 111 - "pragma_var_order.cpp"
Cohesion: 0.29
Nodes (7): Branch(), Call(), dllAddr(), dllPtr(), InjectHacks(), PTMFCrimes, rawPtr

### Community 112 - "ParserCtx"
Cohesion: 0.18
Nodes (12): FileEntry, Parser, ctx, srcInfo, ParserCtx, parent, srcInfo, stream (+4 more)

### Community 113 - "Controller.cpp"
Cohesion: 0.27
Nodes (6): Controller::GetControllerInput(), Controller::GetInput(), Controller::GetJoystickCaps(), Controller::SetButtonFromControllerInputs(), Controller::SetButtonFromDirectInputJoystate(), th06::Controller::GetControllerState()

### Community 114 - "Pscr"
Cohesion: 0.18
Nodes (6): Pscr, base, character, difficulty, score, stage

### Community 115 - "SupervisorState"
Cohesion: 0.17
Nodes (12): SupervisorState, SUPERVISOR_STATE_ENDING, SUPERVISOR_STATE_EXITERROR, SUPERVISOR_STATE_EXITSUCCESS, SUPERVISOR_STATE_GAMEMANAGER, SUPERVISOR_STATE_GAMEMANAGER_REINIT, SUPERVISOR_STATE_INIT, SUPERVISOR_STATE_MAINMENU (+4 more)

### Community 116 - ".SpawnSingleBullet"
Cohesion: 0.20
Nodes (6): BulletTypeInfo, bulletAnmScriptIdx, bulletSpawnEffectDonutAnmScriptIdx, bulletSpawnEffectFastAnmScriptIdx, bulletSpawnEffectNormalAnmScriptIdx, bulletSpawnEffectSlowAnmScriptIdx

### Community 117 - "EclManager"
Cohesion: 0.18
Nodes (4): EclManager, eclFile, subTable, timeline

### Community 122 - "BulletTypeSprites"
Cohesion: 0.18
Nodes (9): BulletTypeSprites, bulletHeight, grazeSize, spriteBullet, spriteSpawnEffectDonut, spriteSpawnEffectFast, spriteSpawnEffectNormal, spriteSpawnEffectSlow (+1 more)

### Community 123 - "Detouring"
Cohesion: 0.18
Nodes (7): Detouring, addressInOriginalBinary, addrToReplace, nameInDllReplacement, replaceWith, stub, DllMain()

### Community 124 - "EclTimelineInstr"
Cohesion: 0.18
Nodes (11): EclRawHeader, mainCount, subCount, subOffsets, timelineOffsets, EclTimelineInstr, arg0, args (+3 more)

### Community 125 - "EclRawInstrAnmSetPosesArgs"
Cohesion: 0.18
Nodes (10): EclRawInstrAnmSetPosesArgs, anmExDefault, anmExFarLeft, anmExFarRight, anmExLeft, anmExRight, EclRawInstrSpellcardStartArgs, spellcardId (+2 more)

### Community 126 - "EclTimelineInstrArgs"
Cohesion: 0.18
Nodes (9): EclRawInstrExInstrArgs, exInstrIndex, EclTimelineInstrArgs, uintVar1, uintVar2, uintVar3, uintVar4, ushortVar1 (+1 more)

### Community 127 - "EnemyManager.cpp"
Cohesion: 0.22
Nodes (4): Enemy::HandleLifeCallback(), Enemy::HandleTimerCallback(), Enemy::ResetEffectArray(), Enemy::UpdateEffects()

### Community 128 - "Catk"
Cohesion: 0.18
Nodes (11): Catk, base, captureScore, characterShotType, idx, name, nameCsum, numAttempts (+3 more)

### Community 129 - "StageMenu"
Cohesion: 0.18
Nodes (5): StageMenu, curState, menuBackground, menuSprites, numFrames

### Community 130 - "coff.py"
Cohesion: 0.20
Nodes (6): BaseType, ComplexType, MachineType, SectionFlags, SpecialSectionNumber, StorageClass

### Community 132 - "BulletAimMode"
Cohesion: 0.20
Nodes (10): BulletAimMode, CIRCLE, CIRCLE_AIMED, FAN, FAN_AIMED, OFFSET_CIRCLE, OFFSET_CIRCLE_AIMED, RANDOM (+2 more)

### Community 133 - "EclRawInstrBulletArgs"
Cohesion: 0.20
Nodes (10): EclRawInstrBulletArgs, angle1, angle2, color, count1, count2, flags, speed1 (+2 more)

### Community 134 - "OptionsCursorPosition"
Cohesion: 0.20
Nodes (10): OptionsCursorPosition, CURSOR_OPTIONS_POS_BOMBCOUNT, CURSOR_OPTIONS_POS_COLORMODE, CURSOR_OPTIONS_POS_EXIT, CURSOR_OPTIONS_POS_KEYCONFIG, CURSOR_OPTIONS_POS_LIFECOUNT, CURSOR_OPTIONS_POS_MUSICMODE, CURSOR_OPTIONS_POS_PLAYSOUNDS (+2 more)

### Community 135 - "PlayerDirection"
Cohesion: 0.20
Nodes (10): PlayerDirection, MOVEMENT_DOWN, MOVEMENT_DOWN_LEFT, MOVEMENT_DOWN_RIGHT, MOVEMENT_LEFT, MOVEMENT_NONE, MOVEMENT_RIGHT, MOVEMENT_UP (+2 more)

### Community 136 - "CSound"
Cohesion: 0.20
Nodes (8): CSound, m_apDSBuffer, m_dwCurFadeoutProgress, m_dwDSBufferSize, m_dwIsFadingOut, m_dwNumBuffers, m_dwTotalFadeout, m_pWaveFile

### Community 137 - "Scope"
Cohesion: 0.22
Nodes (8): Scope, hashMask, nodes, vtable, x10, x4, x8, xC

### Community 138 - "EclRawInstrBulletEffectsArgs"
Cohesion: 0.22
Nodes (9): EclRawInstrBulletEffectsArgs, fvar1, fvar2, fvar3, fvar4, ivar1, ivar2, ivar3 (+1 more)

### Community 139 - "RunningSpellcardInfo"
Cohesion: 0.22
Nodes (6): RunningSpellcardInfo, captureScore, idx, isActive, isCapturing, usedBomb

### Community 140 - "GuiFormattedText"
Cohesion: 0.22
Nodes (5): GuiFormattedText, fmtArg, isShown, pos, timer

### Community 141 - "MsgRawInstr"
Cohesion: 0.22
Nodes (8): MsgRawHeader, instrs, numInstrs, MsgRawInstr, args, argSize, opcode, time

### Community 143 - "ScoreDat"
Cohesion: 0.22
Nodes (8): ScoreDat, csum, dataOffset, fileLen, scores, unk, unk_8, xorseed

### Community 144 - "RawStageHeader"
Cohesion: 0.22
Nodes (9): RawStageHeader, facesOffset, nbFaces, nbObjects, scriptOffset, songNames, songPaths, stageName (+1 more)

### Community 145 - "CStreamingSound"
Cohesion: 0.22
Nodes (6): CStreamingSound, m_bFillNextNotificationWithSilence, m_dwLastPlayPos, m_dwNextWriteOffset, m_dwNotifySize, m_dwPlayProgress

### Community 146 - "update_decompile_stats.py"
Cohesion: 0.50
Nodes (5): create_status_profile(), get_file(), get_unimplemented(), main(), update_svg()

### Community 150 - "Unprotector"
Cohesion: 0.25
Nodes (6): Unprotector, mAddress, mName, mOldProtect, mSize, mSuccess

### Community 151 - "HashNode"
Cohesion: 0.25
Nodes (8): HashNode, hash, keywordType, next, str, tk, xC, VarOrderCB()

### Community 153 - "AnmRawInstr"
Cohesion: 0.25
Nodes (5): AnmRawInstr, args, argsCount, opcode, time

### Community 154 - "UpdateGameMenuState"
Cohesion: 0.25
Nodes (8): UpdateGameMenuState, GAME_MENU_PAUSE_CURSOR_QUIT, GAME_MENU_PAUSE_CURSOR_UNPAUSE, GAME_MENU_PAUSE_OPENING, GAME_MENU_PAUSE_SELECTED_UNPAUSE, GAME_MENU_QUIT_CURSOR_NO, GAME_MENU_QUIT_CURSOR_YES, GAME_MENU_QUIT_SELECTED_YES

### Community 155 - "StageNumber"
Cohesion: 0.25
Nodes (8): StageNumber, EXTRA_STAGE, FINAL_STAGE, STAGE1, STAGE2, STAGE3, STAGE4, STAGE5

### Community 156 - "ResultScreenMainMenuCursor"
Cohesion: 0.25
Nodes (8): ResultScreenMainMenuCursor, RESULT_SCREEN_CURSOR_EASY, RESULT_SCREEN_CURSOR_EXIT, RESULT_SCREEN_CURSOR_EXTRA, RESULT_SCREEN_CURSOR_HARD, RESULT_SCREEN_CURSOR_LUNATIC, RESULT_SCREEN_CURSOR_NORMAL, RESULT_SCREEN_CURSOR_SPELLCARDS

### Community 157 - "RawStageObject"
Cohesion: 0.25
Nodes (7): RawStageObject, firstQuad, flags, id, position, size, zLevel

### Community 160 - "Token"
Cohesion: 0.29
Nodes (5): DoVarOrder(), ExpectToken_shim(), ScanList_shim(), Token, tk

### Community 163 - "Entry"
Cohesion: 0.29
Nodes (7): Entry, name, next, Object, entry, x0, x4

### Community 165 - "BulletState"
Cohesion: 0.29
Nodes (7): BulletState, BULLET_STATE_DESPAWNING, BULLET_STATE_FIRED, BULLET_STATE_SPAWNING_FAST, BULLET_STATE_SPAWNING_NORMAL, BULLET_STATE_SPAWNING_SLOW, BULLET_STATE_UNUSED

### Community 166 - "EclRawInstrBulletRankInfluenceArgs"
Cohesion: 0.29
Nodes (7): EclRawInstrBulletRankInfluenceArgs, bulletRankAmount1High, bulletRankAmount1Low, bulletRankAmount2High, bulletRankAmount2Low, bulletRankSpeedHigh, bulletRankSpeedLow

### Community 169 - "GuiFlags"
Cohesion: 0.29
Nodes (6): GuiFlags, flag0, flag1, flag2, flag3, flag4

### Community 170 - "StageOpcode"
Cohesion: 0.29
Nodes (7): StageOpcode, STDOP_CAMERA_FACING, STDOP_CAMERA_FACING_INTERP_LINEAR, STDOP_CAMERA_POSITION_KEY, STDOP_FOG, STDOP_FOG_INTERP, STDOP_PAUSE

### Community 174 - "RetryGameMenuState"
Cohesion: 0.33
Nodes (6): RetryGameMenuState, RETRY_MENU_CURSOR_NO, RETRY_MENU_CURSOR_YES, RETRY_MENU_OPENING, RETRY_MENU_SELECTED_NO, RETRY_MENU_SELECTED_YES

### Community 175 - "EclRawInstrCallArgs"
Cohesion: 0.33
Nodes (6): EclRawInstrCallArgs, cmpLhs, cmpRhs, eclSub, float0, var0

### Community 176 - "EclRawInstrEnemyCreateArgs"
Cohesion: 0.33
Nodes (6): EclRawInstrEnemyCreateArgs, itemDrop, life, pos, score, subId

### Community 178 - "Difficulty"
Cohesion: 0.33
Nodes (6): Difficulty, EASY, EXTRA, HARD, LUNATIC, NORMAL

### Community 179 - "OrbState"
Cohesion: 0.33
Nodes (6): OrbState, ORB_FOCUSED, ORB_FOCUSING, ORB_HIDDEN, ORB_UNFOCUSED, ORB_UNFOCUSING

### Community 180 - "RawStageInstr"
Cohesion: 0.33
Nodes (5): RawStageInstr, args, frame, opcode, size

### Community 184 - "AnmVmAnchor"
Cohesion: 0.40
Nodes (5): AnmVmAnchor, AnmVmAnchor_Center, AnmVmAnchor_Left, AnmVmAnchor_Top, AnmVmAnchor_TopLeft

### Community 185 - "EclRawInstrAnmSetDeathArgs"
Cohesion: 0.40
Nodes (4): EclRawInstrAnmSetDeathArgs, deathAnm1, deathAnm2, deathAnm3

### Community 187 - "TrackDescriptor"
Cohesion: 0.40
Nodes (4): TrackDescriptor, description, path, title

### Community 188 - "BulletType"
Cohesion: 0.40
Nodes (5): BulletType, BULLET_TYPE_0, BULLET_TYPE_1, BULLET_TYPE_2, BULLET_TYPE_LASER

### Community 189 - "PlayerState"
Cohesion: 0.40
Nodes (5): PlayerState, PLAYER_STATE_ALIVE, PLAYER_STATE_DEAD, PLAYER_STATE_INVULNERABLE, PLAYER_STATE_SPAWNING

### Community 190 - "ZunRect"
Cohesion: 0.40
Nodes (5): ZunRect, bottom, left, right, top

### Community 191 - "StageCameraSky"
Cohesion: 0.40
Nodes (4): StageCameraSky, color, farPlane, nearPlane

### Community 194 - "EclRawInstrJumpArgs"
Cohesion: 0.50
Nodes (4): EclRawInstrJumpArgs, offset, time, var

### Community 196 - "CursorMovement"
Cohesion: 0.50
Nodes (4): CursorMovement, CURSOR_DONT_MOVE, CURSOR_MOVE_DOWN, CURSOR_MOVE_UP

### Community 198 - "SpellcardState"
Cohesion: 0.50
Nodes (4): SpellcardState, NOT_RUNNING, RAN_FOR_60_FRAMES, RUNNING

### Community 199 - "AnmVmBlendMode"
Cohesion: 0.67
Nodes (3): AnmVmBlendMode, AnmVmBlendMode_InvSrcAlpha, AnmVmBlendMode_One

### Community 200 - "AnmVmColorOp"
Cohesion: 0.67
Nodes (3): AnmVmColorOp, AnmVmColorOp_Add, AnmVmColorOp_Modulate

### Community 202 - "EclRawInstrMoveBoundSetArgs"
Cohesion: 0.67
Nodes (3): EclRawInstrMoveBoundSetArgs, lowerMoveLimit, upperMoveLimit

### Community 203 - "EffectCallbackResult"
Cohesion: 0.67
Nodes (3): EffectCallbackResult, EFFECT_CALLBACK_RESULT_DONE, EFFECT_CALLBACK_RESULT_STOP

## Knowledge Gaps
- **1791 isolated node(s):** `name`, `next`, `hash`, `keywordType`, `next` (+1786 more)
  These have ≤1 connection - possible missing edges or undocumented components. (Counts symbols only; 2456 node(s) total have ≤1 connection when file, concept and rationale nodes are included.)
- **64 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `f32` connect `f32` to `EnemyEclInstr.cpp`, `Enemy`, `GameManager`, `EclRawInstrBulletArgs`, `MainMenu`, `Supervisor`, `EclRawInstrBulletEffectsArgs`, `Player`, `Effect`, `AnmVm`, `.StopPlayback`, `Ending`, `SoundPlayer`, `Gui`, `.DrawInner`, `MidiOutput`, `MidiOutput.cpp`, `VertexTex1DiffuseXyz`, `EclRawInstrBulletRankInfluenceArgs`, `Laser`, `CharacterPowerBulletData`, `ZunResult`, `Bullet`, `EclRawInstrCallArgs`, `BulletManager`, `EnemyLaserShooter`, `EnemyBulletShooter`, `ZunRect`, `PlayerBullet`, `StageCameraSky`, `ZunTimer`, `EnemyEclContext`, `PlayerBombInfo`, `ReplayData`, `EclRawInstrLaserArgs`, `D3DXVECTOR3`, `Rng`, `EclRawInstrArg`, `AnmLoadedSprite`, `ZunVec3`, `.SpawnSingleBullet`?**
  _High betweenness centrality (0.122) - this node is a cross-community bridge._
- **What connects `name`, `next`, `hash` to the rest of the system?**
  _1791 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `EclRawInstrOpcode` be split into smaller, more focused modules?**
  _Cohesion score 0.014598540145985401 - nodes in this community are weakly interconnected._
- **Why does `AnmVm` connect `AnmVm` to `StageMenu`, `Enemy`, `MainMenu`, `Player`, `Effect`, `ResultScreen`, `AnmManager`, `Ending`, `Item`, `.DrawInner`, `AnmRawInstr`, `Stage`, `AnmManager.cpp`, `Laser`, `th06.hpp`, `AsciiManager`, `MusicRoom`, `f32`, `PlayerBullet`, `GuiImpl`, `ZunTimer`, `PlayerBombInfo`, `.InitializeVms`, `GuiMsgVm`, `AnmLoadedSprite`, `BulletTypeSprites`?**
  _High betweenness centrality (0.097) - this node is a cross-community bridge._
- **Should `PE` be split into smaller, more focused modules?**
  _Cohesion score 0.039597533268419347 - nodes in this community are weakly interconnected._
- **Why does `PE` connect `PE` to `.get_overlay_data_start_offset`, `pefile.py`, `Structure`, `PEFormatError`, `.adjust_SectionAlignment`, `.dump_info`, `.parse_version_information`, `StructureWithBitfields`?**
  _High betweenness centrality (0.066) - this node is a cross-community bridge._
- **Should `EnemyEclInstr.cpp` be split into smaller, more focused modules?**
  _Cohesion score 0.05228105228105228 - nodes in this community are weakly interconnected._