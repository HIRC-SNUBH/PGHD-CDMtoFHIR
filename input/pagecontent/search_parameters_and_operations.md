### Search Parameters

본 구현 가이드에서 정의된 Search Parameter 목록은 다음과 같습니다.

**Patient**
- [_id](SearchParameter-pghd-cdm-patient-id.html)
- [identifier](SearchParameter-pghd-cdm-patient-identifier.html)
- [organization](SearchParameter-pghd-cdm-patient-organization.html)
- [gender](SearchParameter-pghd-cdm-patient-gender.html)
- [birthdate](SearchParameter-pghd-cdm-patient-birthdate.html)
- [address](SearchParameter-pghd-cdm-patient-address.html)
- [address-state](SearchParameter-pghd-cdm-patient-address-state.html)
- [address-city](SearchParameter-pghd-cdm-patient-address-city.html)
- [address-postalcode](SearchParameter-pghd-cdm-patient-address-postalcode.html)
- [death-date](SearchParameter-pghd-cdm-patient-death-date.html)

**Encounter**
- [_id](SearchParameter-pghd-cdm-encounter-id.html)
- [service-provider](SearchParameter-pghd-cdm-encounter-serviceprovider.html)
- [patient](SearchParameter-pghd-cdm-encounter-patient.html)
- [subject](SearchParameter-pghd-cdm-encounter-subject.html)
- [class](SearchParameter-pghd-cdm-encounter-class.html)
- [status](SearchParameter-pghd-cdm-encounter-status.html)
- [date](SearchParameter-pghd-cdm-encounter-date.html)

**Organization**
- [_id](SearchParameter-pghd-cdm-organization-id.html)
- [name](SearchParameter-pghd-cdm-organization-name.html)
- [type](SearchParameter-pghd-cdm-organization-type.html)
- [address](SearchParameter-pghd-cdm-organization-address.html)
- [address-state](SearchParameter-pghd-cdm-organization-address-state.html)
- [address-city](SearchParameter-pghd-cdm-organization-address-city.html)
- [address-postalCode](SearchParameter-pghd-cdm-organization-address-postalcode.html)

**DeviceUseStatement**
- [_id](SearchParameter-pghd-cdm-deviceusestatement-id.html)
- [subject](SearchParameter-pghd-cdm-deviceusestatement-subject.html)
- [patient](SearchParameter-pghd-cdm-deviceusestatement-patient.html)
- [device.type](SearchParameter-pghd-cdm-deviceusestatement-devicetype.html)

**Observation**
- [_id](SearchParameter-pghd-cdm-observation-id.html)
- [status](SearchParameter-pghd-cdm-observation-status.html)
- [code](SearchParameter-pghd-cdm-observation-code.html)
- [subject](SearchParameter-pghd-cdm-observation-subject.html)
- [patient](SearchParameter-pghd-cdm-observation-patient.html)
- [date](SearchParameter-pghd-cdm-observation-date.html)
- [category](SearchParameter-pghd-cdm-observation-category.html)
- [subject.gender](SearchParameter-pghd-cdm-observation-subject-gender.html)
- [patient.gender](SearchParameter-pghd-cdm-observation-patient-gender.html)
- [deviceUseStartTiming](SearchParameter-pghd-cdm-observation-device-use-start-timing.html)
- [deviceUsetEndTiming](SearchParameter-pghd-cdm-observation-device-use-end-timing.html)
- [device.type](SearchParameter-pghd-cdm-observation-device-type.html)
- [_contained](SearchParameter-pghd-cdm-observation-contained.html)

**Obseravtion component**
- [_id](SearchParameter-pghd-cdm-observation-component-id.html)
- [status](SearchParameter-pghd-cdm-observation-component-status.html)
- [code](SearchParameter-pghd-cdm-observation-component-code.html)
- [component-code](SearchParameter-pghd-cdm-observation-component-component-code.html)
- [subject](SearchParameter-pghd-cdm-observation-component-subject.html)
- [patient](SearchParameter-pghd-cdm-observation-component-patient.html)
- [date](SearchParameter-pghd-cdm-observation-component-date.html)
- [category](SearchParameter-pghd-cdm-observation-component-category.html)
- [subject.gender](SearchParameter-pghd-cdm-observation-component-subject-gender.html)
- [patient.gender](SearchParameter-pghd-cdm-observation-component-patient-gender.html)
- [deviceUseStartTiming](SearchParameter-pghd-cdm-observation-component-device-use-start-timing.html)
- [deviceUsetEndTiming](SearchParameter-pghd-cdm-observation-component-device-use-end-timing.html)
- [device.type](SearchParameter-pghd-cdm-observation-component-device-type.html)
- [_profile](SearchParameter-pghd-cdm-observation-component-profile.html)
- [_contained](SearchParameter-pghd-cdm-observation-contained.html)

**Questionnaire**
- [_id](SearchParameter-pghd-cdm-questionnaire-id.html)
- [status](SearchParameter-pghd-cdm-questionnaire-status.html)
- [title](SearchParameter-pghd-cdm-questionnaire-title.html)
- [code](SearchParameter-pghd-cdm-questionnaire-code.html)

**QuestionnaireResponse**
- [_id](SearchParameter-pghd-cdm-questionnaireresponse-id.html)
- [subject](SearchParameter-pghd-cdm-questionnaireresponse-subject.html)
- [patient](SearchParameter-pghd-cdm-questionnaireresponse-patient.html)
- [authored](SearchParameter-pghd-cdm-questionnaireresponse-authored.html)
- [encounter](SearchParameter-pghd-cdm-questionnaireresponse-encounter.html)
- [questionnaire.id](SearchParameter-pghd-cdm-questionnaireresponse-questionnaire-id.html)
- [questionnaire.status](SearchParameter-pghd-cdm-questionnaireresponse-questionnaire-status.html)
- [questionnaire.title](SearchParameter-pghd-cdm-questionnaireresponse-questionnaire-title.html)
- [questionnaire.code](SearchParameter-pghd-cdm-questionnaireresponse-questionnaire-code.html)

### Operations
본 구현 가이드에서 정의된 Opeation 목록은 다음과 같습니다.

- [observation-snapshot](OperationDefinition-observation-snapshot.html)
- [questionnaireResponse-snapshot](OperationDefinition-questionnaireresponse-snapshot.html)
- [readsnapshot](OperationDefinition-readsnapshot.html)