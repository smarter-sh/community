# Onboarding and offboarding new Code of Conduct Committee members

Different actions on this list must be carried out by different members:

- **Outgoing members:** members who are ending their term
- **Incoming members:** members beginning their term
- **Carryover members:** members mid-way through their term

## Permissions

### Slack Channel Membership

**Who executes:** When offboarding, outgoing members must remove themselves from Slack channels. When onboarding, carryover members must add incoming members.

- [ ] Code of conduct committee Slack channel(s) (public and private) on `kubernetes.slack.com`
- [ ] `#kubernetes-moderators` and `#slack-reports` private channels on `kubernetes.slack.com` 
- [ ] Code of conduct sync Slack channel on `cloud-native.slack.com`

### Kubernetes/community permissions and google permissions

**Who executes:** Carryover members should ensure that outgoing members are removed and incoming members are invited.

- [ ] Update `kubernetes/community` [`sigs.yaml`](/sigs.yaml)
- [ ] Update `kubernetes/k8s.io`:
  - [ ] [`OWNERS_ALIASES`](https://git.k8s.io/k8s.io/OWNERS_ALIASES)
  - [ ] [`groups.yaml`](https://git.k8s.io/k8s.io/groups/committee-code-of-conduct/groups.yaml)
    > **Note:** This file controls access to the mailing list and Google Drive! If you do not update this file, adding people manually (via the UIs) continually revert until this file is updated.
    - [ ] `conduct@kubernetes.io` mailing list
    - [ ] Google drive
- [ ] Update `kubernetes/org`:
  - [ ] [`OWNERS_ALIASES`](https://git.k8s.io/org/OWNERS_ALIASES)
  - [ ] [`config/kubernetes/org.yaml`](https://git.k8s.io/org/config/kubernetes/org.yaml)

## Communications

**Who executes:** Anyone but outgoing members!

- [ ] Give an update at the monthly Community meeting
- [ ] Send an email to the `kubernetes/dev` mailing list

## Knowledge transfer and group procedures

**Who executes:** Carryover members should lead

- [ ] Introduce new members to relevant contacts
- [ ] Re-evaluate weekly meeting time
- [ ] Schedule training and knowledge management sessions for new members
