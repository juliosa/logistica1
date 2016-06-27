boolFalse # bc799737 = Bool ;
 boolTrue # 997275b5 = Bool ;

verdade # 3fedd339 = Verdadeiro ;

vector # 1cb5c415 {t: Tipo} # [t] = Vector t ;

error code # c4b9f9bb: int texto: cadeia = Erro ;

nula # 56730bcc = NULL ;

inputPeerEmpty # 7f3b18ea = InputPeer ;
 inputPeerSelf # 7da07ec9 = InputPeer ;
 inputPeerContact # 1023dbe8 user_id: int = InputPeer ;
 inputPeerForeign # 9b447325 user_id: int access_hash: longa = InputPeer ;
 inputPeerChat # 179be863 chat_id: int = InputPeer ;

inputUserEmpty # b98886cf = InputUser ;
 inputUserSelf # f7c1b13f = InputUser ;
 inputUserContact # 86e94f65 user_id: int = InputUser ;
 inputUserForeign # 655e74ff user_id: int access_hash: longa = InputUser ;

inputPhoneContact # f392b7f4 client_id: longa telefone: cadeia first_name: cadeia last_name: cadeia = InputContact ;

inputFile id # f52ff27f: longas partes: int name: cadeia md5_checksum: cadeia = InputFile ;
 inputFileBig # fa4f0bb5 id: longas partes: int nome: cadeia = InputFile ;

inputMediaEmpty # 9664f57f = InputMedia ;
 inputMediaUploadedPhoto arquivo # 2dc53a7d: InputFile = InputMedia ;
 inputMediaPhoto # 8f2ab2ec id: InputPhoto = InputMedia ;
 inputMediaGeoPoint # f9c44144 geo_point: InputGeoPoint = InputMedia ;
 inputMediaContact # a6e45987 phone_number: cadeia first_name: cadeia last_name: cadeia = InputMedia ;
 inputMediaUploadedVideo # 133ad6f6 id: InputVideo = InputMedia ;
 inputMediaUploadedAudio arquivo # 4e498cab: InputFile duração: int mime_type: cadeia = InputMedia ;
 inputMediaAudio # 89938781 id: InputAudio = InputMedia ;
 inputMediaUploadedDocument arquivo # ffe76b78: InputFile : mime_type cadeia atributos: Vector < DocumentAttribute > = InputMedia ;
 inputMediaUploadedThumbDocument # 41481486 file: InputFile ouro: InputFile : mime_type cadeia atributos: Vector < DocumentAttribute > = InputMedia ;
 inputMediaDocument # d184e841 id: InputDocument = InputMedia ;

inputChatPhotoEmpty # 1ca48f57 = InputChatPhoto ;
 inputChatUploadedPhoto # 94254732 file: InputFile cultura: InputPhotoCrop = InputChatPhoto ;
 inputChatPhoto # b2e1bf08 id: InputPhoto cultura: InputPhotoCrop = InputChatPhoto ;

inputGeoPointEmpty # e4c123d6 = InputGeoPoint ;
 inputGeoPoint # f3b7acc9 lat: double long: double = InputGeoPoint ;

inputPhotoEmpty # 1cd7bf0d = InputPhoto ;
 inputPhoto id # fb95c6c4: longa access_hash: longa = InputPhoto ;

inputVideoEmpty # 5508ec75 = InputVideo ;
 inputVideo id # ee579652: longa access_hash: longa = InputVideo ;

inputFileLocation # 14637196 volume_id: longa local_id: int segredo: longa = InputFileLocation ;
 inputVideoFileLocation # id 3d0364ec: longa access_hash: longa = InputFileLocation ;
 inputEncryptedFileLocation # f5235d55 id: longa access_hash: longa = InputFileLocation ;
 inputAudioFileLocation # 74dc404d id: longa access_hash: longa = InputFileLocation ;
 inputDocumentFileLocation id # 4e45abe9: longa access_hash: longa = InputFileLocation ;

inputPhotoCropAuto # ade6b004 = InputPhotoCrop ;
 inputPhotoCrop # d9915325 crop_left: double crop_top: double crop_width: double = InputPhotoCrop ;

inputAppEvent # 770656a8 tempo: dupla Tipo: cadeia de pares: longa data: cadeia = InputAppEvent ;

peerUser # 9db1bc6d user_id: int = pares ;
 peerChat # bad0e5bb chat_id: int = pares ;

storage.fileUnknown # aa963b05 = storage.FileType ;
 storage.fileJpeg # 7efe0e = storage.FileType ;
 storage.fileGif # cae1aadf = storage.FileType ;
 storage.filePng # a4f63c0 = storage.FileType ;
 storage.filePdf # ae1e508d = storage.FileType ;
 storage.fileMp3 # 528a0677 = storage.FileType ;
 storage.fileMov # 4b09ebbc = storage.FileType ;
 storage.filePartial # 40bc6f52 = storage.FileType ;
 storage.fileMp4 # b3cea0e4 = storage.FileType ;
 storage.fileWebp # 1081464c = storage.FileType ;

fileLocationUnavailable # 7c596b46 volume_id: longa local_id: int segredo: longa = filelocation ;
 filelocation # 53d69076 dc_id: int volume_id: longa local_id: int segredo: longa = filelocation ;

userEmpty # 200250ba id: int = usuário ;
 userSelf # 7007b451 : id int first_name: cadeia last_name: cadeia usuário: cadeia = usuário ;

userProfilePhotoEmpty # 4f11bae1 = UserProfilePhoto ;
 userProfilePhoto # d559d8c8 photo_id: longa photo_small: filelocation photo_big: filelocation = UserProfilePhoto ;

userStatusEmpty # 9d05049 = UserStatus ;
 userStatusOnline # edb93949 expira: int = UserStatus ;
 userStatusOffline # 8c703f was_online: int = UserStatus ;
 userStatusRecently # e26f42f1 = UserStatus ;
 userStatusLastWeek # 7bf09fc = UserStatus ;
 userStatusLastMonth # 77ebc742 = UserStatus ;

chatEmpty # 9ba2d800 id: int = Bate-papo ;
 conversar # 6e9c9bc7 id: int título: corda data: int = Bate-papo ;

chatFull # 630e61be id: int participantes: ChatParticipants chat_photo: Foto notify_settings: PeerNotifySettings = ChatFull ;

chatParticipant # c8d7493e user_id: int inviter_id: int date: int = ChatParticipant ;

chatParticipantsForbidden # fd2bb8a chat_id: int = ChatParticipants ;
 chatParticipants # 7841b415 chat_id: int admin_id: int participantes: Vector < ChatParticipant > Versão: int = ChatParticipants ;

chatPhotoEmpty # 37c1011c = ChatPhoto ;
 chatPhoto # 6153276a photo_small: filelocation photo_big: filelocation = ChatPhoto ;

messageEmpty # 83e5de54 id: int = mensagem ;
 mensagem # 567699b3 bandeiras: int id: int from_id: int to_id: Par de data: int ação: MessageAction = Mensagem ;

messageMediaEmpty # 3ded6320 = MessageMedia ;
 messageMediaPhoto # c8c45a2a foto: Foto = MessageMedia ;
 messageMediaVideo # a2d24290 vídeo: Vídeo = MessageMedia ;
 messageMediaGeo # 56e0d474 geo: GeoPoint = MessageMedia ;
 messageMediaContact # 5e7d2f39 documento: Documento = MessageMedia ;
 messageMediaAudio # c6b68300 áudio: Áudio = MessageMedia ;

messageActionEmpty # b6aef7b0 = MessageAction ;
 messageActionChatCreate # a6638b9a título: cordas usuários: Vector < int > = MessageAction ;
 messageActionChatEditTitle título # b5a1ce5a: cadeia = MessageAction ;
 messageActionChatEditPhoto # 7fcb13a8 foto: Foto = MessageAction ;
 messageActionChatDeletePhoto # 95e3fbef = MessageAction ;
 messageActionChatAddUser # 5e3cfc4b user_id: int = MessageAction ;
 messageActionChatDeleteUser # b2ae9b0c user_id: int = MessageAction ;

diálogo entre pares # ab3a99ac: Par top_message: int UNREAD_COUNT: int notify_settings: PeerNotifySettings = Dialog ;

photoEmpty # 2331b22d id: longa = Foto ;
 photo # 22b56751 id: longa access_hash: longa user_id: int date: int legenda: cadeia geo: GeoPoint tamanhos: Vector < PhotoSize > = Foto ;

photoSizeEmpty tipo # e17e23c: cadeia = PhotoSize ;
 photoSize # 77bfb61b tipo: cadeia local: filelocation w: int h: int size: int = PhotoSize ;
 photoCachedSize tipo # e9a734fa: cadeia local: filelocation w: int h: int bytes: bytes = PhotoSize ;

videoEmpty id # c10658a8: longa = Vídeo ;
 video # 388fa391 id: long access_hash: long user_id: int date: int caption: string duration: int mime_type: string size: int thumb: PhotoSize dc_id: int w: int h: int = Video ;

geoPointEmpty # 1117dd5f = GeoPoint ;
 GeoPoint # 2049d70c longa: double lat: double = GeoPoint ;

auth.checkedPhone # e300cc3b phone_registered: Bool phone_invited: Bool = auth.CheckedPhone ;

auth.sentCode # efed51d9 phone_registered: Bool phone_code_hash: cadeia send_call_timeout: int is_password: Bool = auth.SentCode ;

auth.authorization # f6b673a4 expira: int usuário: Usuário = auth.Authorization ;

auth.exportedAuthorization # df969c2d id: int bytes: bytes = auth.ExportedAuthorization ;

inputNotifyPeer # b8bc5b0c pares: InputPeer = InputNotifyPeer ;
 inputNotifyUsers # 193b4417 = InputNotifyPeer ;
 inputNotifyChats # 4a95e84e = InputNotifyPeer ;
 inputNotifyAll # a429b886 = InputNotifyPeer ;

inputPeerNotifyEventsEmpty # f03064d8 = InputPeerNotifyEvents ;
 inputPeerNotifyEventsAll # e86a2c74 = InputPeerNotifyEvents ;

inputPeerNotifySettings # 46a2ce98 mute_until: int som: cordas show_previews: Bool events_mask: int = InputPeerNotifySettings ;

peerNotifyEventsEmpty # add53cb3 = PeerNotifyEvents ;
 peerNotifyEventsAll # 6d1ded88 = PeerNotifyEvents ;

peerNotifySettingsEmpty # 70a68512 = PeerNotifySettings ;
 peerNotifySettings # 8d5e11ee mute_until: int som: cordas show_previews: Bool events_mask: int = PeerNotifySettings ;

peerSettings # 818426cd bandeiras: # report_spam:? flags.0 verdadeiros = PeerSettings ;

Wallpaper # ccb03657 id: int título: cordas tamanhos: Vector < PhotoSize > color: int = Papel de parede ;
 wallPaperSolid # 63117f24 id: int título: cadeia bg_color: int color: int = Papel de parede ;

inputReportReasonSpam # 58dbcab8 = ReportReason ;
 inputReportReasonViolence # 1e22c78d = ReportReason ;
 inputReportReasonPornography # 2e59d922 = ReportReason ;
 inputReportReasonOther # e1746d0a texto: cadeia = ReportReason ;

userFull # 771095da user: User link: contacts.Link profile_photo: Photo notify_settings: PeerNotifySettings blocked: Bool real_first_name: string real_last_name: string = UserFull ;

contato # f911c994 user_id: int mútua: Bool = Contato ;

importedContact # d0028438 user_id: int client_id: longa = ImportedContact ;

contactBlocked # 561bc879 user_id: int date: int = ContactBlocked ;

contactStatus # d3680c61 user_id: int status: UserStatus = ContactStatus ;

contacts.foreignLinkUnknown # 133421f8 = contacts.ForeignLink ;
 contacts.foreignLinkRequested # a7801f47 has_phone: Bool = contacts.ForeignLink ;
 contacts.foreignLinkMutual # 1bea8ce1 = contacts.ForeignLink ;

contacts.myLinkEmpty # d22a1c60 = contacts.MyLink ;
 contacts.myLinkRequested contato # 6c69efee: Bool = contacts.MyLink ;
 contacts.myLinkContact # c240ebd9 = contacts.MyLink ;

contacts.link # eccea3f5 my_link: contacts.MyLink foreign_link: contacts.ForeignLink usuário: Usuário = contacts.Link ;

contacts.contactsNotModified # b74ba9d2 = contacts.Contacts ;
 contacts.contacts # 6f8b8cb2 contatos: Vector < Contact > usuários: Vector < Usuário > = contacts.Contacts ;

contacts.importedContacts # ad524315 importados: Vector < ImportedContact > retry_contacts: Vector < longo > usuários: Vector < Usuário > = contacts.ImportedContacts ;

contacts.blocked # 1c138d15 bloqueados: Vector < ContactBlocked > usuários: Vector < Usuário > = contacts.Blocked ;
 contacts.blockedSlice # 900802a1 count: int bloqueados: Vector < ContactBlocked > usuários: Vector < Usuário > = contacts.Blocked ;

messages.dialogs # 15ba6c40 diálogos: Vector < diálogo > mensagens: Vector < Mensagem > chats: Vector < Conversa > usuários: Vector < Usuário > = messages.Dialogs ;
 messages.dialogsSlice # 71e094f3 count: int diálogos: Vector < diálogo > mensagens: vetor < Mensagem > chats: Vector < Bate-papo > usuários: vetor < usuário > = messages.Dialogs ;

messages.messages # 8c718e87 mensagens: Vector < Mensagem > chats: Vector < Bate-papo > usuários: Vector < Usuário > = messages.Messages ;
 messages.messagesSlice contagem # b446ae3: int mensagens: Vector < Mensagem > chats: Vector < Bate-papo > usuários: Vector < Usuário > = messages.Messages ;

messages.statedMessages # 969478bb mensagens: Vector < Mensagem > chats: Vector < Bate-papo > usuários: Vector < Usuário > pts: int seguintes: int = messages.StatedMessages ;
 messages.statedMessagesLinks # mensagens 3e74f5c6: Vector < Mensagem > chats: Vector < bate-papo > usuários: Vector < usuário > links: Vector < contacts.Link > pts: int seguintes: int = messages.StatedMessages ;

messages.statedMessage # d07ae726 mensagem: Mensagem chats: Vector < Bate-papo > usuários: Vector < Usuário > pts: int seguintes: int = messages.StatedMessage ;
 messages.statedMessageLink # a9af2881 mensagem: Mensagem chats: Vector < Bate-papo > usuários: Vector < Usuário > links: Vector < contacts.Link > pts: int seguintes: int = messages.StatedMessage ;

messages.sentMessage id # d1f4d35c: int date: int pts: int seguintes: int = messages.SentMessage ;
 messages.sentMessageLink id # e9db4a3f: int date: int pts: int seguintes: int links: Vector < contacts.Link > = mensagens. SentMessage ;

messages.chats # 8150cbd8 chats: Vector < Bate-papo > usuários: Vector < Usuário > = messages.Chats ;

messages.chatFull # e5d7d19c full_chat: ChatFull chats: Vector < Bate-papo > usuários: Vector < Usuário > = messages.ChatFull ;

messages.affectedHistory pts # b7de36f2: int seq: int offset: int = messages.AffectedHistory ;

inputMessagesFilterEmpty # 57e2f66c = MessagesFilter ;
 inputMessagesFilterPhotos # 9609a51c = MessagesFilter ;
 inputMessagesFilterVideo # 9fc00e65 = MessagesFilter ;
 inputMessagesFilterPhotoVideo # 56e9f0e4 = MessagesFilter ;
 inputMessagesFilterPhotoVideoDocuments # d95e73bb = MessagesFilter ;
 inputMessagesFilterDocument # 9eddf188 = MessagesFilter ;
 inputMessagesFilterAudio # cfc87522 = MessagesFilter ;
 inputMessagesFilterAudioDocuments # 5afbf764 = MessagesFilter ;
 inputMessagesFilterUrl # 7ef0dd87 = MessagesFilter ;
 inputMessagesFilterGif # ffc86587 = MessagesFilter ;

updateNewMessage mensagem # 13abdb3: Mensagem pts: int = Atualização ;
 updateMessageID # 4e90bfd6 id: int random_id: longa = Atualização ;
 updateReadMessages mensagens # c6649e31: Vector < int > pts: int = Atualizar ;
 updateDeleteMessages # a92bfe26 mensagens: Vector < int > pts: int = Atualização ;
 updateUserTyping # 5c486927 user_id: int action: SendMessageAction = Atualização ;
 updateChatUserTyping # 9a65ea1f chat_id: int user_id: int action: SendMessageAction = Atualização ;
 updateChatParticipants # 7761198 participantes: ChatParticipants = Atualização ;
 updateUserStatus # 1bfbd823 user_id: int status: UserStatus = atualização ;
 updateUserName # a7332b73 user_id: int first_name: cadeia last_name: cadeia usuário: cadeia = atualização ;
 updateUserPhoto # 95313b0c user_id: int date: int foto: UserProfilePhoto anterior: Bool = atualização ;
 updateContactRegistered # 2575bbb9 user_id: int date: int = atualização ;
 updateContactLink # 51a48a9a auth_key_id: longa data: int dispositivo: cadeia local: cadeia = Atualização ;
 updateNewEncryptedMessage mensagem # 12bcbd9a: encryptedmessage qts: int = Atualização ;
 updateEncryptedChatTyping # 1710f156 chat_id: int = Atualização ;
 updateEncryption # b4a2e88d bate-papo: EncryptedChat data: int = Atualização ;
 updateEncryptedMessagesRead # 38fe25b7 chat_id: int MAX_DATE: int date: int = Atualização ;
 updateChatParticipantAdd # 3a0eeb22 chat_id: int user_id: int inviter_id: int versão: int = Atualização ;
 updateChatParticipantDelete # 6e5f8c22 chat_id: int user_id: int versão: int = Atualização ;
 updateDcOptions # 8e5e9873 dc_options : Vector < DCOption > = Atualize ;
 updateUserBlocked # 80ece81a user_id: int bloqueada: Bool = Atualização ;
 updateNotifySettings # bec268ef pares: NotifyPeer notify_settings: PeerNotifySettings = Atualizar ;
 updateServiceNotification # 382dd3e4 tipo: cadeia mensagem: cadeia media: MessageMedia pop-up: Bool = Atualização ;
 updatePrivacy tecla # ee3b272a: PrivacyKey regras: Vector < PrivacyRule > = Atualização ;
 updateUserPhone # 12b9417b user_id: int telefone: cadeia = Atualização ;

updates.state # a56c2a3e pts: int qts: int date: int seguintes: int UNREAD_COUNT: int = updates.State ;

updates.differenceEmpty # 5d75a138 data: int seguintes: int = updates.Difference ;
 updates.difference new_messages # f49ca0: Vector < Mensagem > new_encrypted_messages: Vector < encryptedmessage > other_updates: Vector < Atualizar > chats: Vector < Bate-papo > usuários: Vector < Usuário > estaduais: updates.State = updates.Difference ;
 updates.differenceSlice new_messages # a8fb1981: Vector < Mensagem > new_encrypted_messages: Vector < encryptedmessage > other_updates: Vector < Atualizar > chats: Vector < Conversa > usuários: Vector < Usuário > intermediate_state: atualizações. Estado = updates.Difference ;

updatesTooLong # e317af7e = Atualizações ;
 updateShortMessage # d3f45784 id: int from_id: int mensagem: cordas pts: int data: int seguintes: int = Atualizações ;
 updateShortChatMessage # 2b2fbd4e id: int from_id: int chat_id: int mensagem: cordas pts: int data: int seguintes: int = atualizações ;
 updateShort # 78d4dec1 atualização: atualização data: int = atualizações ;
 updatesCombined # 725b04c3 atualizações: Vector < Atualizar > usuários: Vector < usuário > chats: Vector < Conversa > data: int seq_start: int seguintes: int = atualizações ;
 atualizações # 74ae4240 atualizações: Vector < Atualizar > usuários: Vector < usuário > chats: Vector < Conversa > data: int seguintes: int = atualizações ;

photos.photos # fotografias 8dca6aa5: Vector < Foto > usuários: Vector < Usuário > = photos.Photos ;
 photos.photosSlice # 15051f54 contagem: int fotos: Vector < Foto > usuários: Vector < Usuário > = photos.Photos ;

photos.photo # 20212ca8 foto: Foto usuários: Vector < Usuário > = photos.Photo ;

upload.file # 96a18d5 Tipo: storage.FileType mtime: int bytes: bytes = upload.File ;

DCOption # 2ec2a43c id: int hostname: cadeia ip_address: cadeia port: int = DCOption ;

configuração # 7dae33e0 data: int expira: int TEST_MODE: Bool this_dc: int dc_options: Vector < DCOption > chat_big_size: int chat_size_max: int broadcast_size_max: int disabled_features: Vector < DisabledFeature > = Configuração ;

nearestDc # 8e1a1775 país: cadeia this_dc: int nearest_dc: int = NearestDc ;

help.appUpdate # 8987f311 id: int crítica: Bool url: string de texto: cadeia = help.AppUpdate ;
 help.noAppUpdate # c45a6536 = help.AppUpdate ;

help.inviteText # 18cb9f78 mensagem: cadeia = help.InviteText ;

encryptedChatEmpty # ab7ec0a0 id: int = EncryptedChat ;
 encryptedChatWaiting # 3bf703dc id: int = EncryptedChat ;

inputEncryptedChat chat_id # f141b5e1: int access_hash: longa = InputEncryptedChat ;

encryptedFileEmpty # c21f497e = EncryptedFile ;
 encryptedFile # 4a70994c id: longa access_hash: long size: int dc_id: int key_fingerprint: int = EncryptedFile ;

inputEncryptedFileEmpty # 1837c364 = InputEncryptedFile ;
 inputEncryptedFileUploaded # 64bd0306 id: longa access_hash: longa = InputEncryptedFile ;
 inputEncryptedFileBigUploaded # 2dc173c8 id: longas partes: int key_fingerprint: int = InputEncryptedFile ;

encryptedmessage # ed18c118 random_id: longa : chat_id int date: int bytes: bytes = encryptedmessage ;

messages.dhConfigNotModified # c0e24635 aleatória: bytes = messages.DhConfig ;
 messages.dhConfig # 2c221edd g: int p: bytes versão: int aleatório: bytes = messages.DhConfig ;

messages.sentEncryptedMessage # 560f8935 data: int = messages.SentEncryptedMessage ;
 messages.sentEncryptedFile # 9493ff32 data: int file: EncryptedFile = messages.SentEncryptedMessage ;

inputAudioEmpty # d95adc84 = InputAudio ;
 inputAudio id # 77d440ff: longa access_hash: longa = InputAudio ;

inputDocumentEmpty # 72f0eaae = InputDocument ;
 inputDocument # 18798952 id: longa access_hash: longa = InputDocument ;

audioEmpty # 586988d8 id: longa = Áudio ;
 áudio id # c7ac6496: longa access_hash: longa user_id: int date: int duration: int mime_type: cadeia size: int dc_id: int = Áudio ;

documentEmpty # 36f8c871 id: longa = Documento ;
 documento # f9a39f4f = Documento ;

help.support # 17c6b5f6 phone_number: corda de usuário: Usuário = help.Support ;

notifyPeer # 9fd40bd8 pares: Intercâmbio = NotifyPeer ;
 notifyUsers # b4c83b4c = NotifyPeer ;
 notifyChats # c007cec3 = NotifyPeer ;
 notifyAll # 74d07c60 = NotifyPeer ;

sendMessageTypingAction # 16bf744e = SendMessageAction ;
 sendMessageCancelAction # fd5ec8f5 = SendMessageAction ;
 sendMessageRecordVideoAction # a187d66f = SendMessageAction ;
 sendMessageUploadVideoAction # 92042ff7 = SendMessageAction ;
 sendMessageRecordAudioAction # d52f73f7 = SendMessageAction ;
 sendMessageUploadAudioAction # e6ac8a6f = SendMessageAction ;
 sendMessageUploadPhotoAction # 990a3c1a = SendMessageAction ;
 sendMessageUploadDocumentAction # 8faee98e = SendMessageAction ;
 sendMessageGeoLocationAction # 176f8ba1 = SendMessageAction ;
 sendMessageChooseContactAction # 628cbc6f = SendMessageAction ;

contactFound # ea879f95 user_id: int = ContactFound ;

contacts.found resultados # 566000e: Vector < ContactFound > usuários: Vector < Usuário > = contacts.Found ;

inputPrivacyKeyStatusTimestamp # 4f96cb18 = InputPrivacyKey ;

privacyKeyStatusTimestamp # bc2eab30 = PrivacyKey ;

inputPrivacyValueAllowContacts # d09e07b = InputPrivacyRule ;
 inputPrivacyValueAllowAll # 184b35ce = InputPrivacyRule ;
 inputPrivacyValueAllowUsers # 131cc67f usuários: Vector < InputUser > = InputPrivacyRule ;
 inputPrivacyValueDisallowContacts # ba52007 = InputPrivacyRule ;
 inputPrivacyValueDisallowAll # d66b66c9 = InputPrivacyRule ;
 inputPrivacyValueDisallowUsers # 90110467 usuários: Vector < InputUser > = InputPrivacyRule ;

privacyValueAllowContacts # fffe1bac = PrivacyRule ;
 privacyValueAllowAll # 65427b82 = PrivacyRule ;
 privacyValueAllowUsers usuários # 4d5bbe0c: Vector < int > = PrivacyRule ;
 privacyValueDisallowContacts # f888fa1a = PrivacyRule ;
 privacyValueDisallowAll # 8b73e763 = PrivacyRule ;
 privacyValueDisallowUsers # usuários c7f49b7: Vector < int > = PrivacyRule ;

account.privacyRules regras # 554abb6f: Vector < PrivacyRule > usuários: Vector < Usuário > = account.PrivacyRules ;

accountDaysTTL # b8d0afdf dias: int = AccountDaysTTL ;

account.sentChangePhoneCode # a4f58c4c phone_code_hash: cadeia send_call_timeout: int = account.SentChangePhoneCode ;

documentAttributeImageSize # 6c37c15c w: int h: int = DocumentAttribute ;
 documentAttributeAnimated # 11b58939 = DocumentAttribute ;
 documentAttributeSticker # fb0a5727 = DocumentAttribute ;
 documentAttributeVideo duração # 5910cccb: int w: int h: int = DocumentAttribute ;
 documentAttributeAudio # 51448e5 duração: int = DocumentAttribute ;
 documentAttributeFilename # 15590068 file_name: cadeia = DocumentAttribute ;

messages.stickersNotModified # f1749a22 = messages.Stickers ;
 messages.stickers # 8a8ecd32 de hash: cordas adesivos: Vector < documento > = messages.Stickers ;

stickerPack # 12b299d4 emoticon: cordas documentos: Vector < longo > = StickerPack ;

messages.allStickersNotModified # e86602c3 = messages.AllStickers ;
 messages.allStickers # dcef3102 de hash: cordas packs: Vector < StickerPack > documentos: Vector < documento > = messages.AllStickers ;

disabledFeature função # ae636f24: cadeia Descrição: cadeia = DisabledFeature ;

---funções---

invokeAfterMsg # cb9f372d {X: Tipo} msg_id: longa consulta: X = X;
 invokeAfterMsgs # 3dc4b4f0 {x: Type} msg_ids: Vector < longo > query: X = X;!
 initConnection # 69796de9 {X: Tipo} api_id: int DEVICE_MODEL: cadeia system_version: cadeia APP_VERSION: cadeia LANG_CODE: seqüência de consulta: X = X;
 invokeWithLayer # da9b0d0d {X: Tipo} camada: int consulta: X = X;

auth.checkPhone # 6fe51dfb phone_number: cadeia = auth.CheckedPhone ;
 auth.sendCode # 768d5f4d phone_number: cadeia phone_code_hash: cadeia = Bool ;
 auth.signUp # 1b067634 phone_number: cadeia phone_code_hash: cadeia phone_code: cadeia = auth.Authorization ;
 auth.logOut # 5717da40 = Bool ;
 auth.resetAuthorizations # 9fab0d1a = Bool ;
 auth.sendInvites # 771c1d97 numeros_ telefone: Vector < cadeia > mensagem: cadeia = Bool ;
 auth.exportAuthorization # e5bfffcd dc_id: int = auth.ExportedAuthorization ;
 auth.importAuthorization # e3ef9613 id: int bytes: bytes = auth.Authorization ;
 auth.bindTempAuthKey # cdd42a05 perm_auth_key_id: longa nonce: longa expires_at: int encrypted_message: bytes = Bool ;
 auth.sendSms # da9f3e8 phone_number: cadeia phone_code_hash: cadeia = Bool ;

account.registerDevice # 446c712c token_type: int token: corda = Bool ;
 account.updateNotifySettings # 84be5b93 pares: InputNotifyPeer configurações: InputPeerNotifySettings = Bool ;
 account.getNotifySettings # 12b3ad31 pares: InputNotifyPeer = PeerNotifySettings ;
 account.resetNotifySettings # db7e1747 = Bool ;
 account.updateProfile # f0888d68 first_name: cadeia last_name: cadeia = usuário ;
 account.updateStatus # 6628562c off-line: Bool = Bool ;
 account.getWallPapers # c04cfac2 = Vector < Papel de parede >;
 account.reportPeer # ae189d5f pares: InputPeer razão: ReportReason = Bool ;
 account.checkUsername # 2714d86c usuário: cadeia = Bool ;
 account.updateUsername # 3e0bdd7c usuário: cadeia = usuário ;
 account.getPrivacy tecla # dadbc950: InputPrivacyKey = account.PrivacyRules ;
 account.setPrivacy # c9f81ce8-chave: InputPrivacyKey regras: Vector < InputPrivacyRule > = account.PrivacyRules ;
 account.deleteAccount # 418d4e0b razão: cadeia = Bool ;
 account.getAccountTTL # 8fc711d = AccountDaysTTL ;
 account.setAccountTTL # 2442485e ttl: AccountDaysTTL = Bool ;
 account.sendChangePhoneCode # a407a8f4 phone_number: cadeia = account.SentChangePhoneCode ;
 account.changePhone # 70c32edb phone_number: cadeia phone_code_hash: cadeia phone_code: cadeia = usuário ;
 account.updateDeviceLocked # 38df3532 período: int = Bool ;

users.getUsers id # d91a548: Vector < InputUser > = Vector < Usuário >;
 users.getFullUser # ca30a5b1 id: InputUser = UserFull ;

contacts.getStatuses # c4a353ee = Vector < ContactStatus >;
 contacts.getContacts # 22c6aa08 de hash: corda = contacts.Contacts ;
 contacts.importContacts # da30b32d contatos: Vector < InputContact > substituir: Bool = contacts.ImportedContacts ;
 contacts.deleteContact # 8e953744 id: InputUser = contacts.Link ;
 contacts.deleteContacts id # 59ab389e: Vector < InputUser > = Bool ;
 contacts.block # 332b49fc id: InputUser = Bool ;
 contacts.unblock # e54100bd id: InputUser = Bool ;
 contacts.getBlocked # f57c350f offset: int limite: int = contacts.Blocked ;
 contacts.exportCard # 84e53737 = Vector < int >;
 contacts.importCard # 4fe196fe export_card: Vector < int > = usuário ;
 contacts.search # 11f812d8 q: corda limite: int = contacts.Found ;
 contatos .resolveUsername # bf0131c usuário: cadeia = usuário ;

messages.getMessages # 4222fa74 id: Vector < int > = messages.Messages ;
 messages.getDialogs # eccf1df6 offset: int max_id: int limit: int = messages.Dialogs ;
 messages.getHistory # 92a1df2f pares: InputPeer offset: int max_id: int limite : int = messages.Messages ;
 messages.search # 7e9f2ab pares: InputPeer offset: int = messages.AffectedHistory ;
 messages.deleteMessages id # 14f2dd0a: Vector < int > = Vector < int >;
 messages.receivedMessages # 28abcb68 max_id: int = Vector < int >;
 messages.setTyping # a3825e50 pares: InputPeer action: SendMessageAction = Bool ;
 messages.sendMessage # 4cde0aab pares: InputPeer mensagem: cadeia random_id: longa = messages.SentMessage ;
 messages.sendMedia # a3c85d76 : pares InputPeer id: Vector < int > = messages.StatedMessages ;
 messages.reportSpam # cf1592db pares: InputPeer = Bool ;
 messages.hideReportSpam # a8f1709b pares: InputPeer = Bool ;
 messages.getPeerSettings # 3672e09c pares: InputPeer = PeerSettings ;
 messages.getChats # 3c6aa187 id: Vector < int > = messages.Chats ;
 messages.getFullChat # 3b831c66 chat_id: int = messages.ChatFull ;
 messages.editChatTitle # b4bc68b5 chat_id: int título: cadeia = messages.StatedMessage ;
 messages.editChatPhoto # d881821d chat_id: int foto: InputChatPhoto = messages.StatedMessage ;
 messages.addChatUser # 2ee9ee9e chat_id: int user_id: InputUser fwd_limit: int = messages.StatedMessage ;
 messages.deleteChatUser # c3c5cd23 chat_id: int user_id: InputUser = messages.StatedMessage ;
 messages.createChat # 419d9aee ​​usuários: Vector < InputUser > title: cadeia = messages.StatedMessage ;
 messages.forwardMessage # 3f3f4f2 pares: InputPeer id: int random_id: longa = messages.StatedMessage ;
 messages.sendBroadcast # 41bb0972 contatos: Vector < InputUser > mensagem: seqüência de mídia: InputMedia = mensagens .StatedMessages ;
 messages.getDhConfig # 26cf8950 versão: int random_length: int = messages.DhConfig ;
 messages.requestEncryption # f64daf43 user_id: InputUser random_id: int g_a: bytes = EncryptedChat ;
 messages.acceptEncryption # 3dbc0415 chat_id: int = Bool ;
 messages.setEncryptedTyping # 791451ed pares: InputEncryptedChat digitação: Bool = Bool ;
 messages.readEncryptedHistory # 7f4b690a pares: InputEncryptedChat MAX_DATE: int = Bool ;
 messages.sendEncrypted # a9776773 max_qts: int = Vector < longo >;
 messages.readMessageContents # 354b5bc2 id: Vector < int > = Vector < int >;
 messages.getStickers # ae22e045 emoticon: cadeia de hash: cadeia = messages.Stickers ;
 messages.getAllStickers # aa3bc868 de hash: cadeia = messages.AllStickers ;

updates.getState # edd4882a = updates.State ;
 updates.getDifference # a041495 pts: int date: int qts: int = updates.Difference ;

photos.updateProfilePhoto # eef579a0 id: InputPhoto cultura: InputPhotoCrop = UserProfilePhoto ;
 photos.uploadProfilePhoto # d50f9c88 id: Vector < InputPhoto > = Vector < longo >;
 photos.getUserPhotos # b7ee553c user_id: InputUser offset: int max_id: int limit: int = photos.Photos ;

upload.saveFilePart # b304a621 file_id: longa file_part: int bytes: bytes = Bool ;
 upload.getFile localização # e3a6cfb5: InputFileLocation offset: int limit: int = upload.File ;
 upload.saveBigFilePart # de7b673d file_id: longa file_part: int file_total_parts: int bytes: bytes = Bool ;

help.getConfig # c4f9186b = Configuração ;
 help.getNearestDc # 1fb33026 = NearestDc ;
 help.getAppUpdate # c812ac7e eventos: Vector < InputAppEvent > = Bool ;
 help.getInviteText # a4a95186 LANG_CODE: cadeia = help.InviteText ;
 help.getSupport # 9cdf08cd = help.Support ;
