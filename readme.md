# Arsys WebFTP — Plugin WordPress

Explorador SFTP integrado en WordPress con autenticación de usuario WP.

## Versiones

| Versión | Archivo | Descripción |
|---|---|---|
| v2.0.0 | arsys-webftp.zip | Requiere Composer (phpseclib3) |
| v2.1.0 | arsys-webftp_2.zip | Sin dependencias, usa php-ssh2 nativo |
| v2.2.0 | arsys-webftp_v2.2.0.zip | Auto-actualización desde GitHub Releases |
| v2.2.1 | arsys-webftp_v2.2.1.zip | Release de prueba — sistema de auto-actualización |
| v2.2.2 | arsys-webftp_v2.2.2.zip | Fix crítico syntax error (retirada) |
| v2.2.3 | arsys-webftp_v2.2.3.zip | Fix descarga de archivos |
| v2.3.0 | arsys-webftp_v2.3.0.zip | Drag & drop, búsqueda de archivos, vista previa de imágenes, log de actividad |
| v2.3.1 | arsys-webftp_v2.3.1.zip | Fix sistema de auto-actualización desde GitHub |
| v2.3.2 | arsys-webftp_v2.3.2.zip | Release de prueba — verificación botón forzar actualización |
| v2.3.3 | arsys-webftp_v2.3.3.zip | Sistema de migraciones de BD automáticas al actualizar |
| v2.3.4 | arsys-webftp\_v2.3.4.zip | Release de prueba — verificación detección automática cada 12h |
| v2.3.5 | arsys-webftp_v2.3.5.zip | Fix actualización automática: error al descomprimir el paquete |
| v2.3.6 | arsys-webftp_v2.3.6.zip | Fix descarga desde GitHub: redirecciones y headers HTTP |
| v2.3.7 | arsys-webftp_v2.3.7.zip | Release de prueba — verificación actualización automática con fix de descarga |
| v2.3.8 | arsys-webftp_v2.3.8.zip | Fix detección y descarga automática desde GitHub |
| v2.3.9 | arsys-webftp_v2.3.9.zip | Release de prueba — verificación ciclo completo de actualización automática |
| v2.4.0 | arsys-webftp_v2.4.0.zip | Fix: aviso de actualización persiste tras actualizar |
| v2.4.1 | arsys-webftp_v2.4.1.zip | Fix aviso actualización persistente — updater restaurado a versión estable |
| v2.4.2 | arsys-webftp_v2.4.2.zip | Fix aviso actualización persistente — versión instalada forzada en transient |
| v2.4.3 | arsys-webftp_v2.4.3.zip | Release de prueba — verificación ciclo completo en WP limpio |
| v2.5.0 | arsys-webftp_v2.5.0.zip | Seguridad: cifrado AES-256-CBC de credenciales + soporte clave privada SSH |
| v2.5.1 | arsys-webftp_v2.5.1.zip | Seguridad: rate limiting login — bloqueo 15min tras 5 intentos fallidos |
| v2.5.2 | arsys-webftp_v2.5.2.zip | Release de demo — verificación sistema de actualización automática |
| v2.5.3 | arsys-webftp_v2.5.3.zip | Seguridad: headers HTTP de seguridad + rotación de token de sesión |
| v2.5.4 | arsys-webftp_v2.5.4.zip | Seguridad: validación MIME/extensiones en subidas (desactivada por defecto, configurable) |
| v2.5.5 | arsys-webftp_v2.5.5.zip | Seguridad: límite edición archivos + timeout búsqueda (desactivados por defecto, configurables) |
| v2.6.0 | arsys-webftp_v2.6.0.zip | Mejoras: breadcrumb clickable, chmod y copiar archivos |


<<<<<<< HEAD
| v2.1.0 | arsys-webftp\_2.zip | Sin dependencias, usa php-ssh2 nativo |

| v2.2.0 | arsys-webftp\_v2.2.0.zip | Auto-actualización desde GitHub Releases |

| v2.2.1 | arsys-webftp\_v2.2.1.zip | Release de prueba — sistema de auto-actualización |

| v2.2.2 | arsys-webftp\_v2.2.2.zip | Fix crítico syntax error (retirada) |

| v2.2.3 | arsys-webftp\_v2.2.3.zip | Fix descarga de archivos |

| v2.3.0 | arsys-webftp\_v2.3.0.zip | Drag \& drop, búsqueda de archivos, vista previa de imágenes, log de actividad |

| v2.3.1 | arsys-webftp\_v2.3.1.zip | Fix sistema de auto-actualización desde GitHub |

| v2.3.2 | arsys-webftp\_v2.3.2.zip | Release de prueba — verificación botón forzar actualización |

| v2.3.3 | arsys-webftp\_v2.3.3.zip | Sistema de migraciones de BD automáticas al actualizar |

| v2.3.4 | arsys-webftp\_v2.3.4.zip | Release de prueba — verificación detección automática cada 12h |

| v2.3.5 | arsys-webftp_v2.3.5.zip | Fix actualización automática: error al descomprimir el paquete |

| v2.3.6 | arsys-webftp_v2.3.6.zip | Fix descarga desde GitHub: redirecciones y headers HTTP |

| v2.3.7 | arsys-webftp_v2.3.7.zip | Release de prueba — verificación actualización automática con fix de descarga |

| v2.3.8 | arsys-webftp_v2.3.8.zip | Fix detección y descarga automática desde GitHub |

| v2.3.9 | arsys-webftp_v2.3.9.zip | Release de prueba — verificación ciclo completo de actualización automática |

| v2.4.0 | arsys-webftp_v2.4.0.zip | Fix: aviso de actualización persiste tras actualizar |

| v2.4.1 | arsys-webftp_v2.4.1.zip | Fix aviso actualización persistente — updater restaurado a versión estable |

| v2.4.2 | arsys-webftp_v2.4.2.zip | Fix aviso actualización persistente — versión instalada forzada en transient |

| v2.4.3 | arsys-webftp_v2.4.3.zip | Release de prueba — verificación ciclo completo en WP limpio |

| v2.5.0 | arsys-webftp_v2.5.0.zip | Seguridad: cifrado AES-256-CBC de credenciales + soporte clave privada SSH |

| v2.5.1 | arsys-webftp_v2.5.1.zip | Seguridad: rate limiting login — bloqueo 15min tras 5 intentos fallidos |

| v2.5.2 | arsys-webftp_v2.5.2.zip | Release de demo — verificación sistema de actualización automática |

| v2.5.3 | arsys-webftp_v2.5.3.zip | Seguridad: headers HTTP de seguridad + rotación de token de sesión |

| v2.5.4 | arsys-webftp_v2.5.4.zip | Seguridad: validación MIME/extensiones en subidas (desactivada por defecto, configurable) |

| v2.5.5 | arsys-webftp_v2.5.5.zip | Seguridad: límite edición archivos + timeout búsqueda (desactivados por defecto, configurables) |

| v2.6.0 | arsys-webftp_v2.6.0.zip | Mejoras: breadcrumb clickable, chmod y copiar archivos |







\## Instalación

=======
## Instalación
>>>>>>> 641bfd7c22e86d1582483010f6b4131bf7b1f1a0
Plugins → Añadir nuevo → Subir plugin → selecciona el ZIP
