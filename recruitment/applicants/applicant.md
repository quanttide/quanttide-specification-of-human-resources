# 申请者

**申请者(`Applicant`)**是指那些对职位感兴趣并已经提交了申请材料的个人。

字段定义如下：

- **ID(`id`)**：系统定义的唯一标识符。
- **状态(`status`)**：申请者在招聘流程中所处的阶段或位置。
- **附件列表(`attachments`)**: 申请者提交的附件，如简历、个人作品等。

## 申请者状态

申请者的状态是指申请者在招聘流程中所处的阶段或位置。定义申请者状态可以帮助招聘团队跟踪每个申请者的进展，管理招聘流程，并及时与申请者沟通。

进行中：

- **草拟中(`drafting`)**：申请者正在创建或修改他们的申请材料，如简历、求职信等，但还没有将这些材料提交给招聘团队。
- **已提交(`submitted`)**：申请者已经完成了职位申请，并提交了所有必要的材料，如简历、求职信等。
- **已候选(`candidated`)**: 已经通过初步筛选，并被视为潜在的雇员人选；已经展示出符合职位要求的基本资格和技能，并可能已经参加了面试或其他评估流程。此时申请者可以被称为“候选人(`Candidate`)”。

结束：

- **已录用(`hired`)**：申请者已经成功通过了所有招聘流程阶段，并被录用为公司的雇员。
- **已拒绝(`rejected`)**：申请者没有通过招聘流程的某个阶段，或者他们的资历不符合职位要求，因此被拒绝。
- **已退出（`withdrew`）**：申请者在招聘流程中自行退出，可能是因为他们接受了其他组织的职位，或者因为他们不再对当前职位感兴趣。
