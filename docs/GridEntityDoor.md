# Class "GridEntityDoor"
### Inherits from Class: {: .inheritance }
[GridEntity](GridEntity.md)
## Functions
### Bar () {: aria-label='Functions' }
[ ](#){: .abrep .tooltip .badge }
#### void Bar ( ) {: .copyable aria-label='Functions' }

___ 
### Can·Blow·Open () {: aria-label='Functions' }
[ ](#){: .abrep .tooltip .badge }
#### boolean CanBlowOpen ( ) {: .copyable aria-label='Functions' }

___ 
### Close () {: aria-label='Functions' }
[ ](#){: .abrep .tooltip .badge }
#### void Close ( boolean Force ) {: .copyable aria-label='Functions' }

___ 
### Get·Sprite·Offset () {: aria-label='Functions' }
[ ](#){: .const .tooltip .badge } [ ](#){: .abrep .tooltip .badge }
#### const [Vector](../Vector) GetSpriteOffset ( ) {: .copyable aria-label='Functions' }

___ 
### Is·Busted () {: aria-label='Functions' }
[ ](#){: .abrep .tooltip .badge }
#### boolean IsBusted ( ) {: .copyable aria-label='Functions' }

___ 
### Is·Key·Familiar·Target () {: aria-label='Functions' }
[ ](#){: .abrep .tooltip .badge }
#### boolean IsKeyFamiliarTarget ( ) {: .copyable aria-label='Functions' }

___ 
### Is·Locked () {: aria-label='Functions' }
[ ](#){: .abrep .tooltip .badge }
#### boolean IsLocked ( ) {: .copyable aria-label='Functions' }

___ 
### Is·Open () {: aria-label='Functions' }
[ ](#){: .abrep .tooltip .badge }
#### boolean IsOpen ( ) {: .copyable aria-label='Functions' }

___ 
### Is·Room·Type () {: aria-label='Functions' }
[ ](#){: .abrep .tooltip .badge }
#### boolean IsRoomType ( [RoomType](../enums/RoomType) Type ) {: .copyable aria-label='Functions' }

___ 
### Is·Target·Room·Arcade () {: aria-label='Functions' }
[ ](#){: .abrep .tooltip .badge }
#### boolean IsTargetRoomArcade ( ) {: .copyable aria-label='Functions' }

___ 
### Open () {: aria-label='Functions' }
[ ](#){: .abrep .tooltip .badge }
#### void Open ( ) {: .copyable aria-label='Functions' }

___ 
### Set·Locked () {: aria-label='Functions' }
[ ](#){: .abrep .tooltip .badge }
#### void SetLocked ( boolean Locked ) {: .copyable aria-label='Functions' }

___ 
### Set·Room·Types () {: aria-label='Functions' }
[ ](#){: .abrep .tooltip .badge }
#### void SetRoomTypes ( [RoomType](../enums/RoomType) CurrentRoomType, [RoomType](../enums/RoomType) TargetRoomType ) {: .copyable aria-label='Functions' }

___ 
### Spawn·Dust () {: aria-label='Functions' }
[ ](#){: .abrep .tooltip .badge }
#### void SpawnDust ( ) {: .copyable aria-label='Functions' }

___ 
### Try·Blow·Open () {: aria-label='Functions' }
[ ](#){: .abrep .tooltip .badge }
#### boolean TryBlowOpen ( boolean FromExplossion ) {: .copyable aria-label='Functions' }
try to open the door by explosive force, true for success 
___ 
### Try·Unlock () {: aria-label='Functions' }
[ ](#){: .abrep .tooltip .badge }
#### boolean TryUnlock ( boolean Force ) {: .copyable aria-label='Functions' }
try to unlock the door using a key, true for success 
___ 
## Variables
### Busted {: aria-label='Variables' }
[ ](#){: .abrep .tooltip .badge }
#### boolean Busted  {: .copyable aria-label='Variables' }

___ 
### Close·Animation {: aria-label='Variables' }
[ ](#){: .abrep .tooltip .badge }
#### string CloseAnimation  {: .copyable aria-label='Variables' }

___ 
### Current·Room·Type {: aria-label='Variables' }
[ ](#){: .abrep .tooltip .badge }
#### [RoomType](../enums/RoomType) CurrentRoomType  {: .copyable aria-label='Variables' }

___ 
### Direction {: aria-label='Variables' }
[ ](#){: .abrep .tooltip .badge }
#### [Direction](../enums/Direction) Direction {: .copyable aria-label='Variables' }

___ 
### Extra·Sprite {: aria-label='Variables' }
[ ](#){: .abrep .tooltip .badge }
#### [Sprite](../Sprite) ExtraSprite  {: .copyable aria-label='Variables' }

___ 
### Extra·Visible {: aria-label='Variables' }
[ ](#){: .abrep .tooltip .badge }
#### boolean ExtraVisible  {: .copyable aria-label='Variables' }

___ 
### Locked·Animation {: aria-label='Variables' }
[ ](#){: .abrep .tooltip .badge }
#### string LockedAnimation  {: .copyable aria-label='Variables' }

___ 
### Open·Animation {: aria-label='Variables' }
[ ](#){: .abrep .tooltip .badge }
#### string OpenAnimation  {: .copyable aria-label='Variables' }

___ 
### Open·Locked·Animation {: aria-label='Variables' }
[ ](#){: .abrep .tooltip .badge }
#### string OpenLockedAnimation  {: .copyable aria-label='Variables' }

___ 
### Previous·State {: aria-label='Variables' }
[ ](#){: .abrep .tooltip .badge }
#### State PreviousState  {: .copyable aria-label='Variables' }

___ 
### Previous·Variant {: aria-label='Variables' }
[ ](#){: .abrep .tooltip .badge }
#### Variant PreviousVariant  {: .copyable aria-label='Variables' }

___ 
### Slot {: aria-label='Variables' }
[ ](#){: .abrep .tooltip .badge }
#### [DoorSlot](../enums/DoorSlot) Slot  {: .copyable aria-label='Variables' }

___ 
### Target·Room·Index {: aria-label='Variables' }
[ ](#){: .abrep .tooltip .badge }
#### int TargetRoomIndex  {: .copyable aria-label='Variables' }
Note: this value only affects the room transition animation and does not actually change the target room.

___ 
### Target·Room·Type {: aria-label='Variables' }
[ ](#){: .abrep .tooltip .badge }
#### [RoomType](../enums/RoomType) TargetRoomType  {: .copyable aria-label='Variables' }

___ 
