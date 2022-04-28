### Search Parameters

본 구현 가이드에서 정의된 Search Parameter 목록은 다음과 같습니다.

**Patient**
- [_id](SearchParameter-PGHD-CDM-patient-id.html)
- [identifier](SearchParameter-PGHD-CDM-patient-identifier.html)
- [organization](SearchParameter-PGHD-CDM-patient-organization.html)
- [gender](SearchParameter-PGHD-CDM-patient-gender.html)
- [birthdate](SearchParameter-PGHD-CDM-patient-birthdate.html)
- [address](SearchParameter-PGHD-CDM-patient-address.html)
- [address-state](SearchParameter-PGHD-CDM-patient-address-state.html)
- [address-city](SearchParameter-PGHD-CDM-patient-address-city.html)
- [address-postalcode](SearchParameter-PGHD-CDM-patient-address-postalcode.html)
- [death-date](SearchParameter-PGHD-CDM-patient-death-date.html)

**Encounter**
- [_id](SearchParameter-PGHD-CDM-encounter-id.html)
- [service-provider](SearchParameter-PGHD-CDM-encounter-serviceprovider.html)
- [patient](SearchParameter-PGHD-CDM-encounter-patient.html)
- [subject](SearchParameter-PGHD-CDM-encounter-subject.html)
- [class](SearchParameter-PGHD-CDM-encounter-class.html)
- [status](SearchParameter-PGHD-CDM-encounter-status.html)
- [date](SearchParameter-PGHD-CDM-encounter-date.html)

**Organization**
- [_id](SearchParameter-PGHD-CDM-organization-id.html)
- [name](SearchParameter-PGHD-CDM-organization-name.html)
- [type](SearchParameter-PGHD-CDM-organization-type.html)
- [address](SearchParameter-PGHD-CDM-organization-address.html)
- [address-state](SearchParameter-PGHD-CDM-organization-address-state.html)
- [address-city](SearchParameter-PGHD-CDM-organization-address-city.html)
- [address-postalCode](SearchParameter-PGHD-CDM-organization-address-postalcode.html)

**DeviceUseStatement**
- [_id](SearchParameter-PGHD-CDM-deviceusestatement-id.html)
- [subject](SearchParameter-PGHD-CDM-deviceusestatement-subject.html)
- [patient](SearchParameter-PGHD-CDM-deviceusestatement-patient.html)
- [device.type](SearchParameter-PGHD-CDM-deviceusestatement-devicetype.html)

**Observation**
- [_id](SearchParameter-PGHD-CDM-observation-id.html)
- [status](SearchParameter-PGHD-CDM-observation-status.html)
- [code](SearchParameter-PGHD-CDM-observation-code.html)
- [subject](SearchParameter-PGHD-CDM-observation-subject.html)
- [patient](SearchParameter-PGHD-CDM-observation-patient.html)
- [date](SearchParameter-PGHD-CDM-observation-date.html)
- [category](SearchParameter-PGHD-CDM-observation-category.html)
- [subject.gender](SearchParameter-PGHD-CDM-observation-subject-gender.html)
- [patient.gender](SearchParameter-PGHD-CDM-observation-patient-gender.html)
- [deviceUseStartTiming](SearchParameter-PGHD-CDM-observation-device-use-start-timing.html)
- [deviceUsetEndTiming](SearchParameter-PGHD-CDM-observation-device-use-end-timing.html)
- [device.type](SearchParameter-PGHD-CDM-observation-device-type.html)
- [_contained](SearchParameter-PGHD-CDM-observation-contained.html)

**Obseravtion component**
- [_id](SearchParameter-PGHD-CDM-observation-component-id.html)
- [status](SearchParameter-PGHD-CDM-observation-component-status.html)
- [code](SearchParameter-PGHD-CDM-observation-component-code.html)
- [component-code](SearchParameter-PGHD-CDM-observation-component-component-code.html)
- [subject](SearchParameter-PGHD-CDM-observation-component-subject.html)
- [patient](SearchParameter-PGHD-CDM-observation-component-patient.html)
- [date](SearchParameter-PGHD-CDM-observation-component-date.html)
- [category](SearchParameter-PGHD-CDM-observation-component-category.html)
- [subject.gender](SearchParameter-PGHD-CDM-observation-component-subject-gender.html)
- [patient.gender](SearchParameter-PGHD-CDM-observation-component-patient-gender.html)
- [deviceUseStartTiming](SearchParameter-PGHD-CDM-observation-component-device-use-start-timing.html)
- [deviceUsetEndTiming](SearchParameter-PGHD-CDM-observation-component-device-use-end-timing.html)
- [device.type](SearchParameter-PGHD-CDM-observation-component-device-type.html)
- [_profile](SearchParameter-PGHD-CDM-observation-component-profile.html)
- [_contained](SearchParameter-PGHD-CDM-observation-contained.html)

**Questionnaire**
- [_id](SearchParameter-PGHD-CDM-questionnaire-id.html)
- [status](SearchParameter-PGHD-CDM-questionnaire-status.html)
- [title](SearchParameter-PGHD-CDM-questionnaire-title.html)
- [code](SearchParameter-PGHD-CDM-questionnaire-code.html)

**QuestionnaireResponse**
- [_id](SearchParameter-PGHD-CDM-questionnaireresponse-id.html)
- [subject](SearchParameter-PGHD-CDM-questionnaireresponse-subject.html)
- [patient](SearchParameter-PGHD-CDM-questionnaireresponse-patient.html)
- [authored](SearchParameter-PGHD-CDM-questionnaireresponse-authored.html)
- [encounter](SearchParameter-PGHD-CDM-questionnaireresponse-encounter.html)
- [questionnaire.id](SearchParameter-PGHD-CDM-questionnaireresponse-questionnaire-id.html)
- [questionnaire.status](SearchParameter-PGHD-CDM-questionnaireresponse-questionnaire-status.html)
- [questionnaire.title](SearchParameter-PGHD-CDM-questionnaireresponse-questionnaire-title.html)
- [questionnaire.code](SearchParameter-PGHD-CDM-questionnaireresponse-questionnaire-code.html)

### Operations
본 구현 가이드에서 정의된 Opeation 목록은 다음과 같습니다.

- [observation-snapshot](OperationDefinition-observation-snapshot.html)
- [questionnaireResponse-snapshot](OperationDefinition-questionnaireresponse-snapshot.html)
- [readsnapshot](OperationDefinition-readsnapshot.html)